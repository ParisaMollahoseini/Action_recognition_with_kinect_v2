<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="Create_model_0"></a>Create model</h1>
<h3 class="code-line" data-line-start=2 data-line-end=3 ><a id="_Explanation_2"></a>✅ Explanation</h3>
<hr>
<p class="has-line-data" data-line-start="5" data-line-end="7">In this section we trained a ResNet-50 model on processed data.<br>
Applying ResNet model is one the transfer learning methods which the model’s weights are pretrained and there is no need to train the whole model again.</p>
<p class="has-line-data" data-line-start="9" data-line-end="10">📌 We used Google Colab framework to use GPU feature and reduce execution time.</p>
<p class="has-line-data" data-line-start="11" data-line-end="12">The whole process of model preperation and train is explained below:</p>
<ul>
<li class="has-line-data" data-line-start="13" data-line-end="14">Upload dataset</li>
<li class="has-line-data" data-line-start="14" data-line-end="15">Install PyTorch library</li>
<li class="has-line-data" data-line-start="15" data-line-end="16">Load ResNet-50 model</li>
<li class="has-line-data" data-line-start="16" data-line-end="17">Convert data to PyTorch dataset</li>
<li class="has-line-data" data-line-start="17" data-line-end="18">Add some layers to the end of ResNet-50 layers and set the output to 5</li>
<li class="has-line-data" data-line-start="18" data-line-end="19">Set model parameters and train model</li>
<li class="has-line-data" data-line-start="19" data-line-end="21">Test model on test data</li>
</ul>
<h3 class="code-line" data-line-start=21 data-line-end=22 ><a id="__How_to_run_21"></a>✅  How to run</h3>
<hr>
<p class="has-line-data" data-line-start="24" data-line-end="30">Follow these steps to run the code:<br>
➙ First you should upload the dataset on google colab files (preferbly on google drive)<br>
➙ Change the directories to your directories on google colab files.<br>
➙ Run the cells up to train cell.<br>
➙ Change the hardware accelerator to GPU from Notebook settings in edit menu.<br>
➙ Run the rest of cells and see the results. 😊</p>
<p class="has-line-data" data-line-start="32" data-line-end="33">This model is inspired from the paper named “Learning and recognizing human action from skeleton movement with deep residual neural networks”.</p>
<h3 class="code-line" data-line-start=34 data-line-end=35 ><a id="_Paper_which_is_used_in_this_project_34"></a>📝 Paper which is used in this project</h3>
<p class="has-line-data" data-line-start="35" data-line-end="38">Pham, H.-H., Khoudour, L., Crouzil, A., Zegers, P., &amp; Velastin, S. A. (2017). Learning and<br>
recognizing human action from skeleton movement with deep residual neural networks. 8th International<br>
Conference of Pattern Recognition Systems (ICPRS 2017).</p>
