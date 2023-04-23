Download Link: https://assignmentchef.com/product/solved-assignment-1-image-classification-knn-svm-softmax-neural-network
<br>
In this assignment you will practice putting together a simple image classification pipeline, based on the k-Nearest Neighbor or the SVM/Softmax classifier. The goals of this assignment are as follows:

<ul>

 <li>understand the basic <strong>Image Classification pipeline</strong> and the data-driven approach (train/predict stages)</li>

 <li>understand the train/val/test <strong>splits</strong> and the use of validation data for <strong>hyperparameter tuning</strong>.</li>

 <li>develop proficiency in writing efficient <strong>vectorized</strong> code with numpy</li>

 <li>implement and apply a k-Nearest Neighbor (<strong>kNN</strong>) classifier</li>

 <li>implement and apply a Multiclass Support Vector Machine (<strong>SVM</strong>) classifier</li>

 <li>implement and apply a <strong>Softmax</strong> classifier</li>

 <li>implement and apply a <strong>Two layer neural network</strong> classifier</li>

 <li>understand the differences and tradeoffs between these classifiers</li>

 <li>get a basic understanding of performance improvements from using <strong>higher-level representations</strong> than raw pixels (e.g. color histograms, Histogram of Gradient (HOG) features)</li>

</ul>

<h2 id="setup">Setup</h2>

Get the code as a zip file <a href="https://cs231n.github.io/assignments/2019/spring1819_assignment1.zip">here</a>.

You can follow the setup instructions <a href="https://cs231n.github.io/setup-instructions">here</a>.

<h3 id="download-data">Download data:</h3>

Once you have the starter code (regardless of which method you choose above), you will need to download the CIFAR-10 dataset. Run the following from the <code class="highlighter-rouge">assignment1</code> directory:

<h3 id="start-ipython">Start IPython:</h3>

After you have the CIFAR-10 data, you should start the IPython notebook server from the <code class="highlighter-rouge">assignment1</code> directory, with the <code class="highlighter-rouge">jupyter notebook</code> command. (See the <a href="https://github.com/cs231n/gcloud/">Google Cloud Tutorial</a> for any additional steps you may need to do for setting this up, if you are working remotely)

If you are unfamiliar with IPython, you can also refer to our <a href="https://cs231n.github.io/ipython-tutorial">IPython tutorial</a>.

<h3 id="some-notes">Some Notes</h3>

<strong>NOTE 1:</strong> There are <code class="highlighter-rouge"># *****START OF YOUR CODE</code>/<code class="highlighter-rouge"># *****END OF YOUR CODE</code> tags denoting the start and end of code sections you should fill out. Take care to not delete or modify these tags, or your assignment may not be properly graded.

<strong>NOTE 2:</strong> The submission process this year has <strong>2 steps</strong>, requiring you to 1. run a submission script and 2. download/upload an auto-generated pdf (details below.) We suggest <strong><em>making a test submission early on</em></strong> to make sure you are able to successfully submit your assignment on time (a maximum of 10 submissions can be made.)

<strong>NOTE 3:</strong> This year, the <code class="highlighter-rouge">assignment1</code> code has been tested to be compatible with python version <code class="highlighter-rouge">3.7</code> (it may work with other versions of <code class="highlighter-rouge">3.x</code>, but we won’t be officially supporting them). You will need to make sure that during your virtual environment setup that the correct version of <code class="highlighter-rouge">python</code> is used. You can confirm your python version by (1) activating your virtualenv and (2) running <code class="highlighter-rouge">which python</code>.

<strong>NOTE 4:</strong> If you are working in a virtual environment on OSX, you may <em>potentially</em> encounter errors with matplotlib due to the <a href="https://matplotlib.org/faq/virtualenv_faq.html">issues described here</a>. In our testing, it seems that this issue is no longer present with the most recent version of matplotlib, but if you do end up running into this issue you may have to use the <code class="highlighter-rouge">start_ipython_osx.sh</code> script from the <code class="highlighter-rouge">assignment1</code> directory (instead of <code class="highlighter-rouge">jupyter notebook</code> above) to launch your IPython notebook server. Note that you may have to modify some variables within the script to match your version of python/installation directory. The script assumes that your virtual environment is named <code class="highlighter-rouge">.env</code>.

<h3 id="q1-k-nearest-neighbor-classifier-20-points">Q1: k-Nearest Neighbor classifier (20 points)</h3>

The IPython Notebook <strong>knn.ipynb</strong> will walk you through implementing the kNN classifier.

<h3 id="q2-training-a-support-vector-machine-25-points">Q2: Training a Support Vector Machine (25 points)</h3>

The IPython Notebook <strong>svm.ipynb</strong> will walk you through implementing the SVM classifier.

<h3 id="q3-implement-a-softmax-classifier-20-points">Q3: Implement a Softmax classifier (20 points)</h3>

The IPython Notebook <strong>softmax.ipynb</strong> will walk you through implementing the Softmax classifier.

<h3 id="q4-two-layer-neural-network-25-points">Q4: Two-Layer Neural Network (25 points)</h3>

The IPython Notebook <strong>two_layer_net.ipynb</strong> will walk you through the implementation of a two-layer neural network classifier.

<h3 id="q5-higher-level-representations-image-features-10-points">Q5: Higher Level Representations: Image Features (10 points)</h3>

The IPython Notebook <strong>features.ipynb</strong> will walk you through this exercise, in which you will examine the improvements gained by using higher-level representations as opposed to using raw pixel values.

5/5 - (3 votes)