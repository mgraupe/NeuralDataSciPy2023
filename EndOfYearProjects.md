# 2023 Course : Neural Data Science with Python 

![Logo](miscFiles/course-logo.png "Course Logo")


### End-of-Course projects 

Your work on the **End-of-Course Project** will make up 50 % of your final course mark. 

One or teams of maximal two students can choose a project from the list below. 
The evaluation will be based on an annotated jupyter-notebook containing your project work and a presentation/discussion of the jupyter-notebook with the jury. The **project submission deadline is January 7th, 2024 (23h59)**. And the **project presentations** 
will take place on **Thursday January 11th, 2024 from 9h00 through 14h00 in room RABELAIS 1 (ground floor, 45 rue des Saints-Pères, 75006 Paris)**. Each presentation is limited to 10 min followed by 5 min of questions. 

The evaluation jury is composed of Heike Stein, Marcel Stimberg, Jonas Ranft and Michael Graupner. 

The annotated jupyter-notebook can be prepared in English or French, up to the choice of the student. Same for the presentation, it can be provided in English or French. 

### Practial tips on the End-of-Course projects 

Find the slides from the presentation of the projects with practial tips [here](lectures/L11_End-of-Course-Projects.pdf). You can 
furthermore download an empty jupter-notebook template [here](miscFiles/empty-project-template.ipynb). 

### Available projects


--------

<table>
<tr>
<th> # </th>
<th> Title </th>
<th>Description</th>
<th>Techniques/skills involvedd</th>
<th>Contact person</th>
</tr>
<!--- ======================== -->
<tr>
<td valign="top">1</td>
<td valign="top"> <b>Testing classifier performance on hand-written digits</b></td>
<td valign="top"> Use the <a href="http://yann.lecun.com/exdb/mnist/">MNIST database</a> of handwritten digits from 0 through 9 and test the performance of different classifiers on how well they can learn to identify individual digits. The dataset has a training set of 60,000 examples, and a test set of 10,000 examples. The digits have been size-normalized and centered in a fixed-size image.

The images from the training dataset would be the input for the classifier and the know identity of the digit would be used to train the classfier. The performance of the classifier is then tested on the test set of images which have never been shown to the classifier. Compare the error rate (the fraction of test dataset images which were not correctly classified) for SVM classifier with different kernel functions (linear, polynomial). 
</td>
<td valign="top">implementing different classifiers and testing performance : SVM with different kernels (linear and nonlinear); reading and treating image data</td>
<td valign="top"><a href="mailto:heike.c.stein@gmail.com ">Heike Stein</a></td>
</tr>
<!--- ======================== -->
<tr>
<td valign="top">2</td>
<td valign="top"> <b>Exploring existence of clusters in hand-written digits</b></td>
<td valign="top"> Use the <a href="http://yann.lecun.com/exdb/mnist/">MNIST database</a> of handwritten digits from 0 through 9 and explore the existence and number of distinct clusters in that dataset. Use the k-means clustering algorithm with different number of pre-determined clusters to find. Evalute the separation between the found clusters using the Silhouette analysis. Use both together, the training set 60,000 examples, and a test set of 10,000 examples. The digits have been size-normalized and centered in a fixed-size image.

The images from the training dataset would be the input for the clustering algorithm. The know identity of the digit can be used to verify whether clusters found corespond to a specific digit. Which digits fall into indistinguishable clusters?   
</td>
<td valign="top">implementing k-means clustering; testing cluster separation with Silhouette analysis; reading and treating image data</td>
<td valign="top"><a href="mailto:heike.c.stein@gmail.com ">Heike Stein</a></td>
</tr>
<!--- ======================== -->
<tr>
<td valign="top">3</td>
<td valign="top"> <b>Extracting and analyzing spike-times from membrane potential recording</b></td>
<td valign="top">Extract spike times from an electrophysiological recordings and characterize spiking statistics. You are provided with whole-cell recordings from medium spiny neurons in the striatum which received pre-synaptic inputs and current injections. The direct current injection elicited action potenials in the recorded neurons. The aim is to extract the times of the presynaptic stimulation - from the stimulus artifact - and the times of the postsynaptic action potentials. Firing rates, the coefficient of variation and the time difference between the pre-synaptic stimulation and the postsynaptic action potentials are to be calculated. 
</td>
<td valign="top">event extraction through thresholding of a time series; calculating spiking statistics such as firing rate, CV, spike-time differences</td>
<td valign="top"><a href="mailto:michael.graupner@parisdescartes.fr">Michael Graupner</a></td>
</tr>

<!--- ======================== -->
<tr>
<td valign="top">4</td>
<td valign="top"> <b>Calculate head-direction tuning curves of presubicluar neurons from calcium imaging </b></td>
<td valign="top">Calculate the preferred head-direction of a presubicular neuron. You are provided with the calcium activity traces of a few neurons and the orientation of the head over time during the entire recording. Combining both allows to evaluate for which head-direction the cell was active. Neurons in the presubiculum are tuned to specific head directions, and this structure is believed to participate in spatial orientation and navigation.
</td>
<td valign="top">calcium imaging analsyis; histogram calculation; tuning curve calculation; peak extraction</td>
<td valign="top"><a href="mailto:michael.graupner@parisdescartes.fr">Michael Graupner</a></td>
</tr>

<!--- ======================== -->
<tr>
<td valign="top">5</td>
<td valign="top"> <b>Calculate head-direction tuning curves of presubicluar neurons from electrophysiological recordings</b></td>
<td valign="top">Calculate the preferred head-direction of a presubicular neuron. You are provided with the spike-times of the neuron and the orientation of the head over time during the entire recording. Combining both allows to evaluate for which head-direction the cell emitted most spikes. Neurons in the presubiculum are tuned to specific head directions, and this structure is believed to participate in spatial orientation and navigation. 
The aim of the project is to establish the preferred head direction of presubicular neurons. For that puropse, the spike-times need to be combined with the known orientation of animals throughout the experiment. Additional, spiking statistics such as firing rate and coefficient of variation are to be calculated. 
</td>
<td valign="top">spike train handling; tuning curve calculation; interpolation; calculate spiking statistics such as firing rate and CV</td>
<td valign="top"><a href="mailto:michael.graupner@parisdescartes.fr">Michael Graupner</a></td>
</tr>


<!--- ======================== -->
<tr>
<td valign="top">6</td>
<td valign="top"> <b>Compute tuning curves of monkey visual cortex neurons</b></td>
<td valign="top">Visual cortex single-unit activity was recorded in awake macaque monkeys actively fixating. The visual stimulation consisted of random dot kinematograms which moved in a different direction for each 500 ms stimulus presentation. The recorded neurons in area MT are directional tuned. The task would be to calculate the peri-stimulus time histogram for each stimulus and determine the directional tuning curve of each recorded neuron.
</td>
<td valign="top">spike train handling; PSTH and tuning curve calculation; calculating spiking statistics such as firing rate</td>
<td valign="top"><a href="mailto:michael.graupner@parisdescartes.fr">Michael Graupner</a></td>
</tr>

<!--- ======================== -->
<tr>
<td valign="top">7</td>
<td valign="top"> <b>Extract whisking activity from mouse video recordings</b></td>
<td valign="top">Mice are filmed with a high-speed camera during a locomotion task. The experiment aims at studying the link between cerebellar neural activity and locomotion. However, mice have to use their whiskers in order to successfully perform the task which consists of walking on bars (similar to a ladder) in the complete darkness. The aim of this project is to extract a measure of whisker activity from the video recordings. Does the engament of the whiskers change dynamically during the task or does the whisker frequency remain constant whenever the animal is walking? 
</td>
<td valign="top">video/image handling and analysis</td>
<td valign="top"><a href="mailto:michael.graupner@parisdescartes.fr">Michael Graupner</a></td>
</tr>

<!--- ======================== -->
<tr>
<td valign="top">8</td>
<td valign="top"> <b>Leaky-Integrate-and-Fire model with refractory period</b></td>
<td valign="top">In this project, you will implement a numerical simulation of the Leaky-Integrate-and-Fire (LIF) neuron model with refractory period, i.e., for which after each spike the membrane potential is frozen for a short period of time during which inputs are not integrated. This refractory period represents roughly the duration of the action potential in real neurons. You will use the Euler method to solve numerically the subthreshold voltage dynamics in the presence of random, fluctuating inputs, and combine this with a threshold detection mechanism to identify spike times and implement the reset. For a fixed choice of input resistance, threshold and reset potential, you will plot the firing rate as a function of the remaining parameters: (i) the mean and (ii) the standard deviation of the input current, and (iii) the duration of the refractory period.
</td>
<td valign="top">simulation of a single neuron model; noise term; numerical integration; spike train analysis</td>
<td valign="top"><a href="mailto:jonas.ranft@ens.psl.eu">Jonas Ranft</a></td>
</tr>

<!--- ======================== -->
<tr>
<td valign="top">9</td>
<td valign="top"> <b>Exponential-Integrate-and-Fire model</b></td>
<td valign="top">The Exponential-Integrate-and-Fire (EIF) neuron model is a slight modification of the classical Leaky-Integrate-and-Fire (LIF) model. Compared to the LIF, the EIF contains an additional, active current that grows exponentially with the potential, characterized by two parameters: a threshold value and the sharpness of the spike onset. This current represents the action-potential-initiating sodium current without explicitly modelling the ion channel dynamics (i.e., no additional variable is introduced). In the EIF, a spike occurs when the potential diverges, which in practice is implemented by comparing the voltage to a large finite value. You will use the Euler method to solve numerically the voltage dynamics in the presence of random, fluctuating inputs, and combine this with a threshold detection mechanism to identify spike times and implement the reset. For a fixed choice of input resistance, threshold parameter and reset potential, you will plot the firing rate as a function of the remaining parameters: (i) the mean and (ii) the standard deviation of the input current, and (iii) the sharpness of the spike onset.
</td>
<td valign="top">simulation of a single neuron model; numerical integration; spike train analysis</td>
<td valign="top"><a href="mailto:jonas.ranft@ens.psl.eu">Jonas Ranft</a></td>
</tr>

<!--- ======================== -->
<tr>
<td valign="top">10</td>
<td valign="top"> <b>Decoding working memory contents from EEG</b></td>
<td valign="top">Human subjects perform an oculomotor delayed response task, in which they see a stimulus on a screen and have to remember its angular location over a brief delay period. During this task, scalp EEG signals are recorded. The project aims at learning to read out  working memory contents from alpha frequency power (8-12 Hz) in EEG, which is known to decrease on electrodes contralaterally to the location of attended or remembered stimuli. To achieve this, you will implement a neural decoder that uses the distribution of signals across different electrodes. There are many methods that can be used for neural decoding, e.g. linear regression or classifiers (such as SVM) which can be coded by hand or called via scikits-learn. An important concept that you will apply during this project is cross-validation, i.e. training your model on one part of the data, and keeping separate "unseen" data apart to validate the model. The dataset consists of an example subject with ~ 1000 trials where different locations were remembered. TIme-resolved alpha power is already extracted from the EEG signals.
</td>
<td valign="top">linear models, classifiers, cross-validation </td>
<td valign="top"><a href="mailto:heike.c.stein@gmail.com ">Heike Stein</a></td>
</tr>

<!--- ======================== -->
<tr>
<td valign="top">11</td>
<td valign="top"> <b>Short-term synaptic plasticity</b></td>
<td valign="top">Starting with the model of a conductance-based synapse from lecture/tutorial 09, implement "short-term synaptic plasticity", i.e. a synapse that gets weaker ("synaptic depression") or stronger ("synaptic facilitation") when activated repeatedly. Consider the model from chapter 3.1.3 in the book Neuronal Dynamics (https://neuronaldynamics.epfl.ch/online/Ch3.S1.html), and demonstrate the plasticity by plotting a figure similar to Figure 3.3 from that chapter.
</td>
<td valign="top">simulation of a spiking neural network; Brian simulator</td>
<td valign="top"><a href="mailto:marcel.stimberg@inserm.fr">Marcel Stimberg</a></td>
</tr>


<!--- ======================== -->
<tr>
<td valign="top">12</td>
<td valign="top"> <b>Coupled oscillators</b></td>
<td valign="top">Implement a simple "network" of two leaky-integrate-and-fire neuron. Each of the neurons should receive a constant input current that makes it spike regularly. Connect the two neurons via a simple synapse (i.e. the first neuron connects to the second, and the second neuron connects to the first). If you start the two neurons with different initial values of their membrane potentials, what behaviour do you see if the two neurons are 1) unconnected, 2) connected with excitatory synapses 3) connected with inhibitory synapses? Neurons of this type are often analysed as "oscillators" that are described by a frequency and a phase. See how this can help you describe the behaviour of the two neurons in the 3 situations considered above.
</td>
<td valign="top">simulation of a simple 2-neuron spiking neural network; Brian simulator</td>
<td valign="top"><a href="mailto:marcel.stimberg@inserm.fr">Marcel Stimberg</a></td>
</tr>
 
<!--- ======================== -->
<tr>
<td valign="top">13</td>
<td valign="top"> <b>Interplay of excitation and inhibition</b></td>
<td valign="top">Create a single LIF neuron, following the model from tutorial/exercise 07 (without synaptic currents/conductances). Connect two, independent Poisson input generators (i.e. PoissonInput) to this neuron, each simulating the input from 1000 neurons, firing with 1Hz (see Brian's documentation for details). One of them should be excitatory with a positive weight w_exc, the other should be inhibitory with a negative weight w_inh. Vary the two weights and consider two scenarios: in the first scenario, disable the spiking threshold for the neuron (for easier analysis), by either removing the threshold condition or by simply setting the threshold value to a very high value. Then, calculate and plot the average membrane potential, and its standard deviation in dependence of the weights. In the second scenario, re-enable the spiking threshold and calculate/plot the average firing rate and the CV of the interspike interval. Consider either running multiple trials or long simulations to get good statistics. Can you make a link between the results for the two scenarios?
</td>
<td valign="top">simulation of neurons and synapses; Brian simulator; basic spike train analysis</td>
<td valign="top"><a href="mailto:marcel.stimberg@inserm.fr">Marcel Stimberg</a></td>
</tr>


<!--- ======================== -->
<tr>
<td valign="top">14</td>
<td valign="top"> <b>Author position and gender bias</b></td>
<td valign="top">The aim of this project is to investigate the fraction of scientific articles published (from the PubMed database) by a female/male scientist as first/last author, and how these fractions have developed over the last 20 years. Please, illustrate with an appropriate visualization your obtained results. 
</td>
<td valign="top">literature searches, visualization of data</td>
<td valign="top"><a href="mailto:karine.audouze@parisdescartes.fr">Karine Audouze</a></td>
</tr>

<!--- ======================== -->
<tr>
<td valign="top">15</td>
<td valign="top"> <b>Research trends in neuroscience</b></td>
<td valign="top">The aim of this project is to explore patterns and extract research trends based on most common keywords in neuroscience publications (i.e. textual information based on the PubMed database). After identifying these research trends, develop a graphical representation of them (e.g. you can generate wordcloud images). Study how such trends changed over time (e.g. 20 years in intervals of 5 years).  
</td>
<td valign="top">literature searches, visualization of data</td>
<td valign="top"><a href="mailto:karine.audouze@parisdescartes.fr">Karine Audouze</a></td>
</tr>
<!--- ======================== -->
<tr>
<td valign="top">16</td>
<td valign="top"> <b>Influential papers in neuroscience</b></td>
<td valign="top">The aim of this project is to identify influential papers in Neuroscience based on citation counts, i.e., which articles and topics received most citations. Compare the impact based on citations with the impact factors of the journals in which the articles are published. Perform this study using the PubMed database and choose a relevant way of visualizing your results.
</td>
<td valign="top">literature searches, visualization of data</td>
<td valign="top"><a href="mailto:karine.audouze@parisdescartes.fr">Karine Audouze</a></td>
</tr>



</table>



