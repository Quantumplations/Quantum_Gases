These files are the Fourier transform of the Rabi oscillations for interaction 1/k_Fa =0.96, T=0.03T_F, and detuning set to the repulsive polaron (0.553E_F). 
Each file is a matrix with dimensions \omega x \Omega. 

I create the plot in matplotlib:
c = plt.pcolormesh(Om,wplot/Om,R_spectra, cmap = 'turbo', vmin = 0.0, vmax = 0.5, shading='gouraud',zorder=-20)

(If this is at all helpful)