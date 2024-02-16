# BioPhotonics_SignalProcessing

## Innovative nano-SPR for rapid, low-limit VLP detection

### Quick Introduction
Efficient early detection of viruses is crucial for disease control. The traditional techniques, such as plaque and hemagglutination assays, are standard but have limitations in calibration and virus type identification, calling for better methods. Recent advancements in technology offer superior virus detection methods, like dynamic light scattering and fluorophore-labeled antibodies for accurate virus quantitation.

Surface plasmon resonance (SPR) is a particularly promising approach due to its label-free, real-time detection capabilities with a simple sample introduction. However, standard SPR technology, which relies on angle measurements through a prism, is not ideal for widespread, high-throughput applications.

To overcome these limitations, we've explored metallic nanostructures for SPR activation, which are highly sensitive but typically require complex equipment. Our innovation utilizes a two-color analysis technique, allowing for direct detection with a conventional color CCD camera, eliminating the need for intricate spectrometers. This method has proven to detect SARS-CoV-2 virus-like particles at concentrations lower than 2 pg/ml, outperforming complex tests like ELISA.

Our approach, leveraging dual-band image capturing and sophisticated analysis software, enhances signal accuracy and reduces noise. It's designed for large-scale use and is compatible with cloud data transmission, making it ideal for home testing. This breakthrough presents a cost-effective, high-throughput, and user-friendly solution for pathogen detection, showing great promise for point-of-care applications.


### Methodology
Our methodology focuses on employing warm white OLED and white LED to differentiate the spectral characteristics necessary for surface plasmon resonance (SPR) detection. By analyzing 20 points across a 40mm × 40mm OLED, we determined a consistent spectrum with several peaks and a dip corresponding to SPR's requirements. The OLED's spectrum proved more effective than LED for deeper SPR dips, crucial for sensitive detection.

For the principle of detection, we leveraged the gold nanoslit arrays' transmission spectra, revealing distinct resonance patterns due to surface and gap plasmon resonances. These patterns, critical for our detection method, are governed by the nanoslits' physical dimensions and the incident light's polarization.

Our chip fabrication entailed creating nanoslit arrays on a polycarbonate film via nanoimprint lithography, followed by gold film deposition. We ensured precise nanoslit dimensions using atomic force microscopy, vital for consistent SPR excitation.

Surface modification of the nanoslit bio-chip was achieved using oxygen plasma treatment, enhancing hydrophilicity—a key factor for effective biological interactions. We tested the biosensing capability with a warm white OLED source and a transmission-type SPR sensing chip, capturing data through a commercially available smartphone camera.

Lastly, our algorithmic framework for automatic chip detection and quality evaluation prioritized the uniformity of the chip image, essential for accurate SPR measurement. We employed a Color Uniformity Score to quantify this uniformity, derived from the standard deviation of color values across the chip image.

This methodology streamlines the detection process, significantly enhancing the ease and accuracy of SPR-based virus detection.

