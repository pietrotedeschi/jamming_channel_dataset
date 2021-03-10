# Modeling a Communication Channel under Jamming - Theory and Applications

The data acquired from the wireless communication channel during our experimental campaign have been also released open-source, to allow researchers and Industry to verify our findings, and to further validate the effectiveness of their methods on real outdoor channel conditions.

We conducted a large experimental campaign, by acquiring real jamming signals outdoor on three different reference channels (500.00MHz, 1,575.42MHz, and 2,437.00MHz), and we analyzed the resulting status of the channel at increasing distance from the jamming source.

To model the variation of the average RSS as a function of the distance $d$ between the transmitter and the receiver, we collected a set of RSS samples for a time $\tau=3$~minutes for a set of different distances D = d_1, d_2, \dots, d_n in an outdoor environment without any obstacle between them, thus making it possible to average out both the slow and the fast fading. It is worth noticing that the experimental measurements are affected by the technology that we have adopted and by the environmental conditions. In all the experiments we can assume LoS between the transmitter and the receiver. Moreover, the nodes were deployed at the same height, so that we cover only the 2-D case deployment.

## Experimental Setup

All the experiments have been performed in an outdoor scenario by using two Software Defined Radios such as the Ettus Research X310 SDR, featuring a UBX160 daughterboard as a jammer transmitter, a MyriadRF LimeSDR as receiver, and a Laptop Dell XPS15 9560, equipped with 32GB of RAM and 8 Intel Core i7700HQ processors running at 2.80 GHz. We acquired the samples by adopting the GNURadio Development Toolkit on three different reference channels (500.00MHz, 1,575.42MHz, and 2,437.00MHz) by using antennas that best fit the frequency range. The antennas gains are set to the maximum for the transmitter and for the receiver in order to have the maximum effectiveness to radiate (in TX) and convert (in RX) the power into a signal.

## Dataset

Each folder contains the RSS samples divided by frequency and for each one them by distances.
