<h1>Dynamic Graph Attention Network (DynGAT) for Fake News Detection</h1>

<p>
This repository provides the implementation of the <strong>Dynamic Graph Attention Network (DynGAT)</strong>, 
designed for detecting fake news on social media platforms. DynGAT leverages the dynamic graph structure of 
social networks to model evolving interactions between users and news sources.
</p>

<h2>Model Highlights</h2>
<ul>
    <li><strong>Graph Construction Module:</strong> Dynamically updates graphs based on temporal and interaction data.</li>
    <li><strong>Graph Attention Module:</strong> Utilizes attention mechanisms to prioritize critical nodes and edges in the graph.</li>
    <li><strong>Deep Learning Classifier:</strong> Classifies news articles into real or fake categories with high accuracy.</li>
</ul>

<h2>Dataset and Results</h2>
<p>
The model has been evaluated on the <strong>TweepFake dataset</strong> (20,712 samples) and has achieved state-of-the-art results:
</p>
<ul>
    <li><strong>Accuracy:</strong> 95%</li>
    <li><strong>Outperforms:</strong></li>
    <ul>
        <li>Static GNN: 87%</li>
        <li>Transformer-based models: 91%</li>
        <li>Hybrid models: 89%</li>
    </ul>
</ul>

<h2>Key Features</h2>
<ul>
    <li>Handles <strong>dynamic graph updates</strong> for time-sensitive social media data.</li>
    <li>Incorporates <strong>attention mechanisms</strong> for prioritizing key interactions.</li>
    <li>Includes an <strong>easy-to-use codebase</strong> for training and testing on custom datasets.</li>
</ul>

<h2>What's in the Repository</h2>
<ul>
    <li><strong>Preprocessing Scripts:</strong> Tools for building dynamic graphs from raw data.</li>
    <li><strong>Model Implementation:</strong> PyTorch-based code for DynGAT.</li>
    <li><strong>Training and Evaluation Scripts:</strong> Sample configurations for running experiments.</li>
    <li><strong>Coming Soon:</strong> Pre-trained weights to reproduce results effortlessly.</li>
</ul>

<h2>Get Started</h2>
<p>
Clone this repository, explore the code, and adapt it for your research or practical applications in combating misinformation!
</p>

<h2>About the Authors</h2>
<p>
This repository is associated with the research article titled: 
<strong>"Dynamic Graph Attention Network with Sentiment Analysis for Fake News Detection in Social Networks"</strong>, 
which will be published in the journal <strong>Web Research</strong>.
</p>
<p>
<strong>1st Author:</strong> Fatemeh Jokar (Corresponding Author)<br>
<strong>Affiliation:</strong> Department of Computer Engineering, Faculty of Computer Engineering and Electrical Engineering, Shahid Bahonar Technical and Vocational University, Shiraz, Iran<br>
<strong>Email:</strong> <a href="mailto:shekufeh.j@gmail.com">shekufeh.j@gmail.com</a>
</p>
