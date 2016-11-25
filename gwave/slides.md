% Gravitational Waves Data Analysis
% Shahnawaz Ahmed
% 25 November 2016


LIGO
--------------------

* The Laser Interferometer Gravitational-Wave Observatory

* Two observatories - Hanford and Livingston

* Michelson interferometers of arm length around 4 km

* Fabry Perot addition to increase the effective arm length

* Detects strain in mirror position by interferometry

Michelson Interferometer 
------------------------
<img src="michelson.jpg " height = "500">

Fabry Perot addition
------------------------
<img src="fabry.jpg" height = "500">

Principle
---------

* Speed of light is constant 

* Difference in path lengths leds to interference

* Different from the antena principle, hence no relation to lengths

* Longer path gives better strain precision

Data
---------

* Time series data of strain

<img src="fig1.png" height = "500"> 

Noise
-----------
* More than 99 % data is noise 

* Seismic Noise

* Thermal Noise

* Photon shot noise

* Muon Shower noise

Spectral density
----------------------
* Fourier transform of signal. (ASD)

<img src="fig02.png" height = "500"> 

Noise removal
-------------
* Whitening 

* Notch filtering

<img src="fig4.png" height = "400">

Linear time invariant systems
-----------------------------

* Relationship between input signal and output

* Characterized by impulse response of system

<img src="impulse.png" height = "300">

Convolution
-----------
* Output given by convolution of input with impulse response

<img src="conv_eqn.png">

* Convolution theorem : Convolution is product in frequency domain

<img src="conv_fourier.png">

Filters
-------
* Filters are nothing but LTI systems with specific impulse response

<img src="filter_tf.png" height = "400">

Low pass filter
---------------

* Ideal transfer function in frequency domain is rect(x)

<img src="rect.png" height = "250">

Low pass filter
---------------

* Filter transfer function with Bandwith B is : 

<img src="lpf_tf.png" height = "100">

Matched filter
--------------
* Signal corrupted by linear noise

<img src="matched_input.png" height = "100">

* Maximize the SNR

<img src="snr.png" height = "100">

Matched filter
--------------
* Transfer function is same as the know signal 

<img src="matched_tf.png" height = "100">

Matched filter
--------------
* Output is the desired signal

<img src="matched_demo.png" height = "500">


Data Analysis
-------------

* ASD of data

<img src="fig02.png" height = "500">

Data Analysis
-------------

* Whitened data

<img src="fig3.png" height = "500">

Data Analysis
-------------

* Matched waveform

<img src="fig2q.png" height = "500">