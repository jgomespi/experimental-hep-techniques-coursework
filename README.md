# Experimental High-Energy Physics Techniques Coursework

Educational laboratory and data-analysis notebooks from the graduate course **Técnicas de Análise de Dados para Física de Altas Energias**, at Universidade do Estado do Rio de Janeiro (UERJ).

This repository collects a sequence of experimental exercises focused on instrumentation, detector signals, calibration, counting statistics, timing measurements, and data analysis methods used in high-energy physics laboratories.

The material is complementary to the final CMS Open Data Upsilon analysis project. While the Upsilon project applies analysis techniques to public collider data, this repository documents the experimental and instrumental foundations developed throughout the course.

## Repository structure

    notebooks/
      01_signal_transmission_and_impedance.ipynb
      02_gamma_spectroscopy_calibration.ipynb
      03_geiger_muller_plateau_dead_time.ipynb
      04_scintillator_pmt_characterization.ipynb
      05_coincidence_timing.ipynb
      06_adc_signal_pedestal_analysis.ipynb

    data/
      gamma_spectroscopy/
      geiger_muller/
      scintillator_pmt/
      coincidence/
      adc/

    docs/
      README.md

    results/
      figures/

## Topics covered

1. Signal transmission, impedance matching, and pulse-shape behavior.
2. Gamma spectroscopy and energy calibration with radioactive sources.
3. Geiger-Muller detector plateau studies, background rates, and dead-time estimation.
4. Scintillator and photomultiplier characterization.
5. Coincidence timing measurements.
6. ADC-based pedestal, charge, and signal analysis.

## Technical stack

- Python
- Jupyter Notebook
- NumPy
- pandas
- matplotlib
- Experimental data analysis
- Radiation-detector instrumentation

## Scope

This is an educational coursework repository. It is preserved as a public portfolio example of experimental physics data analysis, detector instrumentation, reproducible notebook organization, and scientific documentation.

The repository contains only course material and local experimental data files. It does not contain CMS-internal documentation, private collaboration material, or unpublished collaboration-restricted analysis content.

## Relation to other projects

The final course project based on CMS Open Data is available separately as:

    cms-opendata-upsilon-analysis
