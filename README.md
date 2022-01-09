# skr
Theoretical Error Model to estimate the secure key rate in a conservative QKD system

------------------------------------------------------------------------------------

This error model considers the paper Ma2007, where an entanlged photon source was sent to Alice and Bob, who performs local projective measurements on the photons. In this paper, pulsed laser statistics are used, which have to be changed when using continous-wave lasers. Then, the probability of a click considering, amongst other parameters, noise counts, error probability, loss. With this, the QBER is calculated. In the end, the Koashi and Preskill's security proof (which includes the Shannon-entropy) is applied to finally get a secure key rate estimation (dimension [1/s]).

This function can be used to depict the secure key rate over, e.g., the total link loss. With the definition of mean photon pair number /mu=brightness /times coincidence window, it can be shown with respect to the intensity, as well.
