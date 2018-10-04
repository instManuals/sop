---
output:
  html_document:
    number_sections: yes
    theme: simplex
  pdf_document:
    number_sections: yes
---

# Agilent 1220 Infinity LC with UV Detector {-}

AF | 2018-10-04

> *If you encounter problems while running the instrument, please use submit an [**Instrument Incident Report**](https://docs.google.com/forms/d/e/1FAIpQLSc96MiK73kKP06KEZpR0-O7zETCLvWgQtLp_bKEynosUKqpNg/viewform) with a description of your problem.  **For urgent problems please report to Al Fischer, NS 209, dfischer@wcu.edu, x2695!***

# Login

1. Login to Windows using the username **./labuser** and the password **labuser**.
1. Open the HPLC software by clicking the **HPLC Software & Usage Log** shortcut on the Desktop.
1. If you have not already done so, use the form in the browser window that opens to reserve the instrument and log your time using it. (Please check the calendar first to make sure no one else has reserved it.)

# Load a Method

1. Load your method by clicking on the **Method and Run Control** pane on the left hand side of the screen, selecting the **Methods** tab, and double-clicking the method you wish to use.
1. (*Advanced*) If you need to create a new method, click **Method > Save Method As ...** and save a template as a new name.
1. (*Advanced*) To edit the new method, click **Method > Edit Entire Method**, select the portions you wish to edit, click **OK**, and edit the method as necessary.

# Warm Up the Instrument

1. Ensure there is enough solvent for you run in the solvent bottles on top of the instrument.     
      
      > *NEVER let the solvent level get below the level of the filter in the bottle! NEVER let air get into the HPLC plumbing!*

1. Right click on the solvent bottle pictures in the main panel of the HPLC software and enter the approximate solvent levels you observed in the bottles.
1. Open the top/front cover the the HPLC and open the priming valve by turning the black knurled knob on the front of the pump a couple of turns.  This ensures no air will enter the column.
1. Click the green **On** button In the main window of the HPLC software to turn on the pump, column heater, and lamp.
1. After the pumps have been on for roughly 2 minutes *and you do no see air bubbles exiting the valve into the waste line*, you may close the priming valve by turning the black knob until it's closed.
1. Allow the system to run until you observe a stable absorbance baseline in the real-time read out.

# Prepare a Sequence

1. Click on the **Sequence templates** tab under *Method and Run Control* and choose the sequence you wish to use or modify (only modify your own sequence files).
1. To use it as a template for a new sequence, click **Sequence > Save Sequence As** and enter a filename.
1. Click on **Sequence > Sequence Parameters** and enter a filename in the **Subdirectory** field.
1. Open the sequence table by clicking **Sequence > Sequence Table...**.  Edit the resulting sequence table as necessary and press **OK** when finished; an example is given below.

# Run Samples

1. Press the **Play Sequence** button in the main window to start your sequence.

# Analyze and Export

1. Select the **Data Analysis** pane and choose the sequence containing the data you wish to view/analyze/export.
1. Select the sample you wish to view/analyze/export from the sequence.
1. If you prefer to do data analysis in the software you may now do so.  Otherwise, export your chromatogram to a CSV (recommended).
		1. Choose **File > Export File > CSV**.
		1. Select **Signal**.
		1. Choose your file path.
		1. Select the option containing **Wavelength=230 nm**

# Shutdown

1. Press the red **Off** button in the main HPLC control window.
1. Go to **Instrument > More Grad. Pump > Pump Power - Switch Off**.     

      > *You must complete this step or the pump will not turn off and the solvent bottles will run dry!*
		
1. Close the software and logoff from the computer.
1. Remove your samples from the autosampler tray and clean up your work area.
