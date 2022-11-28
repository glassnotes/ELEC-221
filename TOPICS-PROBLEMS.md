# Topic list and suggested problems

(Note: this table will be updated with additional chapter 10-11 problems on 6 December after Lecture 25 is finished)

| Chapter | Topic | Sections covered | Lectures | Suggested problems |
|:----|-|-|-|-|
| 1 | Signals and Systems | All | 1, 3 | 1.3, 1.9, 1.15-1.19, 1.26-1.28, 1.40-1.42, 1.46 |
| 2 | LTI Systems | 2.0-2.4 | 2 | 2.7, 2.13-2.15, 2.49-2.51|
| 3 | Fourier Series | All | 3, 4, 5, 6  | 3.8, 3.13-3.16, 3.22, 3.24-3.28, 3.33-3.39| 
| 4 | CT Fourier transform | All | 8, 9, 10 | 4.5-4.9, 4.18, 4.19, 4.21-4.23, 4.26, 4.33, 4.34, 4.36. 4.49 |
| 5 | DT Fourier transform | All | 12, 13  | 5.1-5.7, 5.13, 5.14, 5.19, 5.20, 5.29, 5.33-5.36 |
| 6 | Time/frequency characterization | All | 15, 16 | 6.2, 6.4, 6.15, 6.21a-c, 6.23, 6.27, 6.28, 6.32, 6.33, 6.35-6.37, 6.39, 6.41, 6.42, 6.65|
| 7 | Sampling | All | 17, 18 | 7.1-7.7, 7.17, 7.18, 7.20, 7.21, 7.25, 7.30, 7.32  | 
| 8 | Communication systems | 8.0-8.4, 8.8 | 20, 21 | 8.1, 8.2, 8.4, 8.7-8.9,  8.15, 8.17-8.19, 8.21, 8.22, 8.26, 8.28,  8.32, 8.40, 8.41 |
| 9 | Laplace transform | 9.0-9.3, 9.5-9.7.4 | 22, 23, 24 |  9.1-9.9,  9.13-9.16, 9.21, 9.22, 9.26,  9.29, 9.32, 9.33, 9.48| 
| 10 | Z-transform | 10.0-10.3, 10.5-10.7 | 24, 25 | 10.1-10.8, 10.21-10.23, 10.26 | 
| 11 | Feedback systems | 11.0-11.2 | 24, 25|  11.1-11.4 | 



## Learning outcomes by lecture

### Lecture 1

 * Define signals and systems, and provide real-world examples of each
 * Express continuous-time and discrete-time signals as functions mathematically and in Python
 * Apply time shifts, time scaling, and time reversal transforms to a signal
 * Identify whether a system has the following properties: linear, causal, memoryless, time invariant, stable, invertible |

### Lecture 2

 * Define the DT/CT unit impulse and step functions
 * Define the impulse response
 * Express a system using the DT convolution sum and CT convolution integral
 * Apply key properties of the convolution sum/integral to determine the response of compound LTI systems

### Lecture 3

 * Express CT periodic signals as linear combinations of complex exponential functions
 * Use the convolution sum/integral to show that complex exponentials are eigenfunctions of LTI systems
 * Express a CT signal as a Fourier series, and compute its Fourier coefficients

### Lecture 4

 * State the Dirichlet criteria and determine whether a signal can be expressed in terms as a Fourier series
 * Describe the Gibbs phenomenon
 * State the key properties of Fourier series
 * Compute the power and energy of a signal, and state Parseval's theorem for CT periodic signals
	 
### Lecture 5

 * Compute the fundamental period and frequency of a DT signal
 * Express DT periodic signals as Fourier series and compute the Fourier coefficients
 * Compute the frequency response of a system, and determine how it responds to a complex exponential signal

### Lecture 6

 * Define filters and construct a set of basic frequency-selective filters 
 * Plot the frequency response of a filter in CT and DT
 * Define and distinguish between finite-impulse-response (FIR) and infinite-impulse-response (IIR) filters in DT

### Lecture 7 (hands-on)

(*LOs for hands-on lectures are included for completion only; these topics will not be covered on the exam*)

  * Describe how the process of music equalization works from a signals and systems perspective
  * Apply the FFT and related methods to a signal using Python and NumPy
  * Use the FFT to manipulate and modify audio signals 
  
### Lecture 8

 * Explain the concept of CT Fourier transform, and distinguish it from the CT Fourier series
 * Compute the Fourier spectrum of a CT signal
 * Describe how the Fourier transform relates impulse and frequency response of a system

### Lecture 9

   * State sufficient criteria for a signal to have a Fourier transform
   * Compute the Fourier transform of a periodic signal
   * Leverage key properties of Fourier transform to simplify its computation
   * Describe the duality between time and frequency domains
   * Use convolution property to determine output of LTI systems
  
### Lecture 10

   * Describe the multiplication property of the Fourier transform
   * Describe the behaviour of the Fourier transform under differentiation and integration
   * Use the convolution property to characterize LTI systems based on differential equations
  
### Lecture 12

 * Compute the DT Fourier transform of non-periodic DT signals
 * State key properties of the DTFT 
 * Leverage convolution properties of DTFT to analyze the behaviour of LTI systems

### Lecture 13

 * Distinguish between the discrete-time Fourier transform and the discrete Fourier transform
 * Describe the fast Fourier transform (FFT) algorithm
 * Implement a basic FFT algorithm and state its algorithmic scaling

### Lecture 14 (hands-on)

 * define and compute the Fourier transform of two-dimensional signals
 * describe the role of a spectrum's magnitude and phase in image processing 
 * apply simple filters to modify images in Python 

### Lecture 15

 * express a frequency response in the magnitude-phase representation
 * differentiate between linear and non-linear phase responses
 * compute the group delay of a frequency response

### Lecture 16

 * define and compute the unit step response of a system
 * plot frequency response using a Bode plot
 * characterize the oscillatory behaviour of CT systems described by second-order differential equations

### Lecture 17

 * state the sampling theorem
 * define the Nyquist sampling rate and determine if a sampling rate is sufficient to reconstruct a signal
 * construct systems of filters to interpolate a signal from its samples
 * describe the phenomenon of aliasing

### Lecture 18

 * describe the frequency domain effects of sampling from a discrete signal
 * decimate and interpolate a DT signal
 * determinate how decimation and interpolation affect the spectrum of a signal

### Lecture 19 (hands-on)

 * apply effects to digital sound using feedback, delay, and modulation
 * simulate the sound of plucked strings using the Karplus-Strong algorithm 

### Lecture 20

 * perform sinusoidal amplitude modulation (AM) and demodulation
 * describe the process of frequency-domain multiplexing
 * differentiate between double- and single-sideband modulation

### Lecture 21

(*Only the first LO here will be covered on the exam*)

 * perform amplitude modulation on a discrete-time signal
 * describe two approaches to frequency modulation
 * modulate and demodulate to perform frequency-shift keying
 * explain (at a high level) how cell phone communication works

### Lecture 22

 * distinguish between the Fourier transform and the Laplace transform
 * compute the Laplace transform and its region of convergence (ROC) for some basic signals
 * represent a ROC using a pole-zero plot
 * compute the inverse Laplace transform of basic signals using the ROC

### Lecture 23

 * apply key properties of the Laplace transform to its computation
 * use the Laplace transform to determine whether a system is causal or stable
 * compute the Laplace transform of systems described by constant-coefficient DEs

### Lecture 24

 * compute system functions for feedback systems
 * use the Laplace transform to design an inverse system
 * define the z-transform, and compute it and its ROC for basic signals

### Lecture 25

 *TBD*
 
 