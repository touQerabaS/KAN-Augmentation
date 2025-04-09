<h1>Data Augmentation in Training Kolmogorov-Arnold Networks: Injecting
Noise to Images</h1>
<h2>Image Classification with Caltech-101, CIFAR-10, CIFAR-100, and STL-10 </h2>
<h2>Overview</h2>
        <p>This repository contains various Jupyter notebooks that demonstrate image classification tasks using popular image datasets: <strong>Caltech-101</strong>, <strong>CIFAR-10</strong>, <strong>CIFAR-100</strong>, and <strong>STL-10</strong>. The project is aimed at developing and testing machine learning models on these datasets for research and development purposes.</p>
<h2>Datasets</h2>
<ul>
    <li><strong>Caltech-101</strong>: A dataset containing 101 object categories, designed for image classification tasks.</li>
    <li><strong>CIFAR-10</strong>: A dataset with 10 object classes, commonly used for evaluating machine learning models.</li>
    <li><strong>CIFAR-100</strong>: Similar to CIFAR-10, but with 100 object classes.</li>
    <li><strong>STL-10</strong>: A dataset with 10 classes, similar to CIFAR-10 but with higher resolution images.</li>
</ul>
<h2>Requirements</h2>
<p>To run the code, ensure you have the following dependencies installed:</p>
<ul>
    <li>Python 3.10+</li>
    <li>Jupyter Notebook or JupyterLab</li>
    <li>Required libraries (listed below)</li>
</ul>
<p>You can install the necessary libraries using the following commands:</p>
<pre>
    <code>
pip install numpy pandas matplotlib scikit-learn tensorflow keras
    </code>
</pre>
<h2>Setup</h2>
<ol>
    <li>Clone the repository to your local machine:</li>
    <pre>
        <code>
git clone &lt;repository_url&gt;
cd &lt;repository_folder&gt;
        </code>
    </pre>
    <li>Install the required libraries mentioned in the requirements section.</li>
</ol>
<h2>Usage</h2>
<p>Each Jupyter notebook contains detailed instructions on how to load and preprocess the datasets, as well as how to implement and train machine learning models.</p>
<ul>
    <li><strong>Caltech-101</strong>: The notebook demonstrates the usage of Caltech-101 images, including loading the dataset, preprocessing images, and applying classification algorithms.</li>
    <li><strong>CIFAR-10</strong>: A classification model using the CIFAR-10 dataset.</li>
    <li><strong>CIFAR-100</strong>: A more complex classification task with 100 classes.</li>
    <li><strong>STL-10</strong>: A dataset with higher resolution images for classification.</li>
</ul> 
<h2>Types of Noise Used</h2>
        <p>Different types of noise are added to the datasets to test the robustness of the machine learning models:</p>
        <ul>
            <li><strong>Gaussian Noise</strong>: Random noise with a normal distribution, often added to simulate real-world imperfections.</li>
            <li><strong>Salt and Pepper Noise</strong>: Randomly occurring black and white pixels in an image that simulate corrupted or missing data.</li>
            <li><strong>Speckle Noise</strong>: Granular noise that appears similar to salt and pepper noise but with a finer distribution of random variations in pixel intensity.</li>
            <li><strong>Poisson Noise</strong>: A type of noise that occurs in images captured in low-light conditions or with low-quality cameras, leading to random variations in pixel values.</li>
            <li><strong>Impulse Noise</strong>: Sharp, sudden spikes in pixel values, similar to salt and pepper noise but with higher magnitude spikes.</li>
            <li><strong>Color Noise</strong>: Distortions in the color channels of the image, which can affect the overall color balance and perception.</li>
        </ul>
<h2>Example</h2>
<p>After setting up the environment and loading the desired notebook, you can run the code in the following order:</p>
<ol>
<li>Load the dataset.</li>
<li>Preprocess images (resize, normalize, etc.).</li>
<li>Define and compile a model (e.g., KAN).</li>
<li>Train the model and evaluate its performance.</li>
<li>Visualize the results (accuracy, loss, confusion matrix).</li>
</ol>
<p>Each notebook will include sample code to guide you through these steps.</p>
<h2>Contributions</h2>
<p>Feel free to fork this repository, contribute by opening issues, or submitting pull requests.</p>
<h2>License</h2>
<p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>
    
    
   
    
