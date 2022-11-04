This is the readme for model code for the paper

Wang XJ, Rinzel J, Rogawski MA (1991) A model of the T-type calcium
current and the low-threshold spike in thalamic neurons.
J Neurophysiol 66:839-850

The model code was implemented in NEURON by Tom Morse.

First 400 words of the abstract from the paper:

1. A model of the transient, low-threshold voltage-dependent (T-type)
Ca2+ current is constructed using recent whole-cell voltage-clamp
data from enzymatically isolated rat thalamocortical relay neurons.
The T-type Ca2+ current is described according to the Hodgkin-Huxley
scheme, using the m3h format, with rate constants determined from the
experimental data (22-24 degrees C; extracellular Ca2+ concentration
[Ca2+]o = 3 mM).
2. The T-type Ca2+ current inactivates rapidly during maintained
depolarization (time constant, Tau h approximately 20 ms at -20 mV),
yet recovery from inactivation is slow (time constant, Tau_r
approximately 270 ms at -80 mV). To reconcile these observations, a
two-step kinetic scheme is proposed for the inactivation gate. Each of
the time constants in this scheme is voltage dependent, with a maximum
at about -85 mV (45 ms for one and 275 ms for the other).
3. Numerical simulations of recovery in a two-pulse, voltage-clamp
protocol compare favorably with experimental results obtained by
Coulter et al. as well as those obtained in an independent series of
experiments with guinea pig thalamic neurons ([Ca2+]o = 10 mM).
4. For current-clamp simulations, a leakage current gL (V-VL) is
included; with VL = -65 mV, the calculated resting membrane potential
is -63 mV.
5. It is shown that the T-type Ca2+ current together with the leakage
current suffices to describe the low-threshold spike (LTS), a slow,
triangular-shaped depolarizing event that can be evoked only from
relatively hyperpolarized membrane potentials and that underlies the
burst firing of Na(+)-dependent action potentials in thalamic
neurons. Outward currents are not required to reproduce the basic
shape of the LTS.
6. The LTS can be activated with either a depolarizing current step
from a sufficiently hyperpolarized level or on termination of a
hyperpolarizing current step. In either case, the amplitude of the LTS
is a monotonically increasing, sigmoid-shape function of the
hyperpolarizing current step intensity.
7. Because of the slower kinetic step of the channel's inactivation
gate, our model predicts that recovery of the LTS to greater than
one-half amplitude would require a prolonged hyperpolarization of
greater than 100 ms (at body temperature). This imposes an upper limit
(approximately 10 Hz) on the frequency of repetitive hyperpolarization
that can elicit a train of LTSs and hence on the frequency of any
rhythm that requires LTS-mediated bursting of thalamic neurons.

Usage instructions:
Auto-launch from ModelDB and press the fig 3 button to recreate fig 3.

or

Microsoft Windows: download and expand the archive.  Compile the mod
files with mknrndll. Double click on mosinit.hoc to start up the
figure 3 simulation.

Unix: Download and expand the archive. Compile the mod files by cd'ing
to the archive directory and running nrnivmodl.  Start the simulation
with the command "nrngui mosinit.hoc", and press the fig 3 button.

MAC: Download and expand the archive.  Drag and drop the newly created
folder, ca_t_lva onto the mknrndll icon.  When mknrndll completed drag
the folder again onto the nrngui icon.  When NEURON starts, load the
mosinit.hoc file from the neuron main menu file menu, then press the
fig 3 button.

Please address any question's about the paper to Xiao-jing Wang, and
any questions about the model code to Tom Morse.

Changelog
=========

* 20220924: Update MOD files to avoid declaring variables and functions with the same name.
  See https://github.com/neuronsimulator/nrn/pull/1992

