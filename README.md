<h1>Readers' emotion detection</h1>

Bi-LSTM attention model research <a href="https://journalofbigdata.springeropen.com/articles/10.1186/s40537-022-00614-2">Readers’ affect: predicting and understanding readers’ emotions with deep learning. Anoop et al.</a>

<h2>Datasets for readers' emotion detection and code for preprocess</h2>
<p>Dataset must be extracted and pathes in notebook must be adapted.</p>
<p>First notebook to run - semeval2007. It will preprocess data into csv files.</p>
<h2>Bi-LSTM-attention</h2>
<p>You need pretrained glove embedding before running notebook.</p>
<p>bilstm_attn_try applies model to semeval2007 dataset.</p>
<p>results:</p>
<p>Acc@1: 0.5060</p>
<p>APd: 0.5223</p>
<p>APe: 0.5267</p>
<p>RMSED: 0.1631</p>
<p>WDD: 0.1009</p>
<h2>BERT approach</h2>
<p>transformer_model_for_ed uses BERT fine-tunung</p>
<p>results:</p>
<p>Acc@1: 0.7120</p>
<p>APd: 0.7432</p>
<p>APe: 0.7320</p>
<p>RMSED: 0.0752</p>
<p>WDD: 0.0735</p>
