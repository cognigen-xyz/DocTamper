#### An example of dirs structure: <Br/>

---DocTamper/ <Br/>
&emsp;| <Br/>
&emsp;---qt_table.pk <Br/>
&emsp;---fph.py <Br/>
&emsp;---dtd.py <Br/>
&emsp;---swins.py <Br/>
&emsp;---ic15metric.py <Br/>
&emsp;---json2ic15.py <Br/>
&emsp;---infer_sroie.py <Br/>
&emsp;---tsroie_deteval.py <Br/>
&emsp;---pths/ <Br/>
&emsp;&emsp;| <Br/>
&emsp;&emsp;---dtd_sroie.pth <Br/>
&emsp;&emsp;---swin_imagenet.pt <Br/>
&emsp;&emsp;---vph_imagenet.pt <Br/>
&emsp;---sroie_test_1011.json <Br/>
&emsp;---test/ <Br/>
&emsp;&emsp;| <Br/>
&emsp;&emsp; ---X00016469670.jpg <Br/>
&emsp;&emsp; ---X00016469671.jpg <Br/>
&emsp;&emsp; ---...... <Br/>
      
#### An example command to reproduce the results: <Br/>

<code>
python json2ic15.py
CUDA_VISIBLE_DEVICES=0 python infer_sroie.py
python tsroie_deteval.py
</code>

We use the IC15 metric following the work "Detecting Tampered Scene Text in the Wild".