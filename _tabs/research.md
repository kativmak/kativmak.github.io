
# 
 Research



# How do supernova remnants cool?


## I. Morphology, optical emission lines, and shocks


Supernovae (SNe) inject $\sim 10^{51}$ erg in the interstellar medium, thereby shocking and heating the gas. 
A substantial fraction of this energy is later lost via radiative cooling. 
I developed a post-processing module CESS for the [FLASH](https://flash.rochester.edu/site/flashcode/) code to calculate the cooling radiation from shock-heated gas using collisional excitation data from [MAPPINGS V](https://bitbucket.org/RalphSutherland/mappings/src/public/). 
However, optical emission lines ([O III] (λ5007), [N II] (λ6583), [S II] (λ6717), Hα (λ6365), Hβ (λ4861)) are usually best observable.
We find that the optical emission lines are affected by the SNR’s complex structure and its projection onto the plane of the sky because the escaping line luminosity can be reduced by 10 - 80% due to absorption along the line-of-sight.
It allows for a direct comparison of simulations with observational data and hence critically testing observational diagnostics.


 [CESS: Cooling Emission in the optical band from Supernovae in (M)HD Simulations](https://github.com/kativmak/CESS)


## II. Unsupervised machine learning analysis of supernova remnants


With my bachelor student, Polina Smirnova, we analysed optical emission from the simulation dataset of supernova remnants interacting with molecular clouds using unsupervised machine learning.
We find that the presence or absence of magnetic fields has no statistically significant effect on the optical line emission, but the ambient density distribution at the site of the supernovae changes the entire evolution and morphology of the SN remnant.


# Testing the fossil field hypothesis:


## could strongly magnetised OB stars produce all known magnetars?


Stars of spectral types O and B produce neutron stars (NSs) after supernova explosions. Most NSs are strongly magnetised including normal radio pulsars with $B \propto 10^{12}$~G and magnetars with $B\propto 10^{14}$~G. A fraction of 7-12~per~cent of massive stars are also magnetised with $B\propto 10^3$~G and some are weakly magnetised with $B\propto 1$~G. It was suggested that magnetic fields of NSs could be the fossil remnants of magnetic fields of their progenitors. My master thesis was dedicated to study this hypothesis.


First, we gather all modern precise measurements of surface magnetic fields in O, B and A stars. Second, we estimate parameters for the log-normal distribution of magnetic fields using
maximum likelihood analysis to estimate parameters of the
magnetic field distribution of B stars and found $\mu\_B = 2.83\pm 0.1$ $\log\_{10}$~(G), σ=0.65\pm 0.09$ for strongly magnetised and &mu\_B = 0.14\pm 0.5$ $\log\_{10}$~(G), $\sigma=0.7\_{-0.27}^{+0.57}$ for weakly magnetised. Third, we assume that the magnetic field of pulsars and magnetars have 2.7 DEX difference in magnetic fields and magnetars represent 10% of all young NSs and run population synthesis code NINA. We found that it is impossible to simultaneously reproduce pulsars and magnetars populations if the difference in their magnetic fields is 2.7 DEX. Therefore, we conclude that the simple fossil origin of the magnetic field is not viable for NSs.


 [NINA (Nova Investigii Neutronicorum Astrorum](https://github.com/ignotur/NINA)



