🪐 Rossiter-McLaughlin Simulation and Sodium Line Analysis

This Python script simulates the Rossiter-McLaughlin (RM) effect during a planetary transit using a limb-darkened rotating star model. It further generates synthetic spectra, applies Doppler shifts due to stellar rotation and planetary motion, and visualizes the planetary absorption features around the sodium (Na D1 and D2) lines



📌 Main Features

    Simulates RM effect using the PyAstronomy RmcL model.

    Builds a synthetic stellar spectrum with limb darkening and center-to-limb intensity variations.

    Models stellar rotation and its effect on the observed line profiles.

    Applies planet occultation using a 2D stellar disk grid and synthesizes transit spectra.

    Shifts spectra into the planet rest frame.

    Visualizes Na I absorption during transit using:

        Normalized 1D spectra

        2D residual maps

        Star-planet position maps on the stellar surface


🧰 Dependencies

Make sure to install the following packages:

pip install numpy matplotlib scipy astropy PyAstronomy spectrum-overload
