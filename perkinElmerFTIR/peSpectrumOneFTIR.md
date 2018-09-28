---
output:
  html_document: 
    number_sections: yes
    theme: united
  pdf_document: 
    number_sections: yes
---
# Perkin Elmer Spectrum One FT-IR Spectrometer {-}
AF | 2018-09-13

> *If you encounter problems while running the Spectrum One, please use submit an [**Instrument Incident Report**](https://docs.google.com/forms/d/e/1FAIpQLSc96MiK73kKP06KEZpR0-O7zETCLvWgQtLp_bKEynosUKqpNg/viewform) with a description of your problem.  **For urgent problems please report to Al Fischer, NS 209, dfischer@wcu.edu, x2695!***

# Start Up

1. Login to the computer using the ID `.\labuser` and the password `labuser`.
1. If you did not reserve the instrument in advance, click on the **Calendar** shortcut on the desktop to reserve the instrument and log your time.
1. Open the **Spectrum IR** software by clicking the shortcut on the Desktop.  Select *labuser* when prompted.
1. Enter the extents of the wavelength range you desire in the **Start (cm $^{-1}$)** and **End (cm $^{-1}$)** boxes at the top left of the screen.
1. Set the collection time by choosing the unit (scans [default], minutes, or seconds) and the desired quantity.
1. Enter the sample identifier in the **Sample ID** box or make note of the default name so you can find it later.  (This is the filename for your sample.)
1. Choose the folder you want to save your data to:
	1. Click on the **Instrument** icon under the *Setup* pane on the right side of the software window.
	1. In the box on the bottom of the window, select the *Setup Instrument Data Collection* tab.
  1. Click checkbox next to the Save box and click the **...** box in the *Save Export Location* box to choose your file path.  This will automatically save you data as a SP (spectrum) file.
	1. Click checkbox next to the export data button and click the **...** box in the *Save Export Location* box to choose you file path.  This will automatically save your data to a CSV file.

# Collect Data (with the ATR Accessory)

1. Remove the light blue cover that is on the ATR cell and set it aside on top of the instrument. Loosen the post if necessary by rotating the knurled know on top of the IR counter clockwise and swing the arm so that it aligns with the cutout in the cover once the post has raised enough to give it enough clearance.
1. Click the **Background** button to acquire a background for your sample.
1. Load your sample:

	- *For liquid samples:*
	    1.  Place a drop on the ATR window.  If you are using a non-volatile liquid you do not need to lower the press; if using a volatile liquid, you may need to lower the press to ensure the liquid does not evaporate before the spectrum can be acquired.
	    1.  Click **Scan** (orange play button in top ribbon) to begin acquiring data.

	- *For solid samples:*
		  1. Make sure your solid is in powder form (or a film for polymers).
		  1. Place a small amount of the solid on the ATR window.
		  1. Press **Scan**.
		  1. Turn the knurled knob on the post clockwise while monitoring the force gauge until it is between 60 and 70.
		  1. Press **Scan** again to acquire the spectrum.
1. When the scan is complete, clean your sample off of the ATR window:
	- *For liquid samples*, remove the top stainless steel disc and use a Kimwipe to remove the liquid from the disc and window; use a solvent such as acetone if necessary.
	- *For solid samples*, remove the top stainless steel disc use a small brush to brush the sample into a beaker, weigh boat, etc., and discard the solid sample appropriately.  Use a Kimwipe moistened with solvent (e.g. acetone) to clean any residue off the disc and window.
1. Repeat steps 2--4 as necessary for more background and sample measurements.

# Explore the Data

- Use the **Samples View** tab to interact with your data.
- To zoom, hold down the left mouse button, draw a box around the area of interest, and double click in the box.
- To zoom out, click the **Auto XY** icon.
- To label peaks toggle the **Labels** button.  To adjust label positions, click and drag; you may also delete individual labels.  To adjust how many/which peaks get labelled, go to **Peak Detection** window pane and adjust the appropriate parameter.
- Click the **Cursor** button for a moveable cursor that you can use to manually find the frequency of each peak.
- To integrate a peak, click **Peak Area/Height** and move the cursor to the peak you wish to integrate and clicking add in the **Calculate** Table tab.  You can also adjust the x limits of each peak by clicking and dragging the triangle/line markers.  Repeat this process until all peaks have been integrated and then click OK next to the **Calculate** table.  The results will display in the **Peak Table** tab.
- To adjust the graph axes, go to the View pane, choose the **Setup View Axes** tab, and enter the ranges you wish to use.
- One you have your graph displayed the way you like it, you may print a hard copy to the `\\NEON\` printer.

# Shut Down

1. Ensure that you have set the data path back to the default path to avoid having others save to your folder!
	1. Click `Setup > Instrument > Setup Instrument Data Collection` and set the file path to `C:\Users\labuser\Documents\spectrumOneDataFolder`
1. Exit the Spectrum IR software and choose *Exit without saving data* when prompted (assuming you have already saved it!).
1. Log out of Windows.
1. Cover the ATR window with the light blue cover and lightly clamp it in place.

> *Please do not turn the FT-IR off.  It requires at least 2 hours to warm up after being turned off.*
