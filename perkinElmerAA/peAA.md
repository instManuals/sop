---
output:
  pdf_document: 
    number_sections: yes
  html_document: 
    number_sections: yes
    theme: united
---
Perkin Elmer PinAAcle 900F Atomic Absorption Spectrometer {-}
--------
AF | 2018-09-20

> If you encounter problems while running the instrument, please use submit an [**Instrument Incident Report**](https://docs.google.com/forms/d/e/1FAIpQLSc96MiK73kKP06KEZpR0-O7zETCLvWgQtLp_bKEynosUKqpNg/viewform) with a description of your problem.  **For urgent problems please report to Al Fischer, NS 209, dfischer@wcu.edu, x2695!**

# Be Safe {-}

> *The AA uses an open flame and compressed, flammable gases that present unique safety hazards*

- *Never* leave the flame unattended. You must be present during the entire analysis.
- Don't touch the flame or anything near it.
- The flame generates UV light.  Don't open the cover or look directly at the flame without UV-blocking goggles.
- Don't over-pressurize the acetylene line.
- You may turn the instrument off in an emergency by using the green power switch on the front.

# Prepare
1. If you have not already done so, open the [web broswer, check the instrument calendar, and reserve/log your time](https://www.wcu.edu/learn/departments-schools-colleges/cas/science-and-math/chemphys/instrumentation/instrumentation-schedules/pe-faas-schedule/) on the instrument (use the `neon` computer).
1. Check the pressures in the gas cylinders and transfer lines:
      - **Air:** Regulator set to 35-75 psi (350-525 kPa)
      - **Acetylene:** Regulator set to 12-14 psi (80-95 kPa) and tank pressure >85 psi (600 kPa).

1. Check the drain tubing and waste bottle to ensure everything is connected, there are no kinks, and the waste bottle is below the maximum fill level.
1. Check the level of the DI water reservoir. If there isn't enough water for your run, remove the filter and transfer line and place it immediately in the spare bottle.

      > *Make sure the filter does not become contaminated -- never touch it or the transfer line and never set it down on anything!*

# Power On and Login
1. Turn on the exhaust hood with the "**light switch**" on the cabinet under the instrument.
1. Turn on the instrument with the **green power switch** on the bottom right corner of the instrument.
1. Open the valve on the acetylene tank. Ensure that the line pressure is 12-14 psi (80*95 kPa) and that the tank pressure is > 85 psi (600 kPa).

      > *Never exceed 15 psi (100 kPa) on the acetylene regulator! Acetylene may spontaneously explode at pressures >100 kPa!*

      > *If the acetylene regulator falls below 85 psi (600 kPa) solvent carryover may occur.  Acetone may then be present in the flame and affect your results.*

1. Open the valve for the compressed air.  Check that the line pressure is about 60 psi (400 kPa).
1. Login to the computer using the username `.\labuser` and the password `labuser`.

# Run the instrument
1. Open the **Syngistix** software.
1. In the browser window that opens up, use the form to reserve the instrument and log your time.
1. Load a method or create a new method.     

    A) *Load a method*: Navigate to the **Analysis Tab > Method > Load**.

    B) *Create a new method:* Navigate to the **Analysis Tab > Method > Load**

1. Edit the method for your analysis.  Start with default parameters and make small tweaks as necessary.     
    1. In the **Spectrometer Tab** select **Background Corrected AA**.     
    1. In the **Calibration Tab**, enter your standard concentrations and their autosampler locations, and make sure you are using the correct type of calibration.
1. Enter your sample information in **Analysis Tab > Sample Info > Open/New**.  Make sure to include the autosampler location for each sample, and create names that are unique to your project/lab group.
1. Create an analysis method:
    1. Navigate to **Analysis Tab > Analysis**.
    1. In the **Automated Tab** slecect "Use active method ..." (for one sample) or "Specify methods ... " (for multiple samples).
    1. Specify the method names in the table.  Double click to select another method.
    1. Select **Create a results data set file**.  *Write this name down in your lab notebook*
    1. Select **Rebuild List** (right side of window)
1. Turn the lamp(s) by navigating to **Instrument Tab > Lamp Setup** and clicking the dot for the lamp you wish to use.
1. Align the burner:
    1. Begin the burner alignment procedure by clicking the **Align Burner** button and following the instructions in the resulting window.
    1. When prompted by the Align Burner instructions, turn on the flame on by navigating to **Instrument Tab > Flame Control** and clicking the grey **standby symbol**.
    1. When prompted by the Align Burner instructions, begin aspirating a representative sample by selecting **Instrument Tab > Go to A/S Location** and entering the location of the sample you wish to aspirate.

      > *Note that the proper burner alignment will vary based on your analyte.*

1.  In **Analysis Tab > Analysis**, double check all analysis parameters you entered earlier, and click **Analyze All** to commence analysis.

      > ***You MUST be present during the entire analysis.  NEVER leave the flame unattended! If you must leave, select*** *Stop Analysis* ***in the Analysis Tab.***

1. To view your calibration curve in real time, select the **Results Tab > Calibration**; to view your sample data, select **Results Tab > Results**.

# Shutdown

1. When you are finished running your samples aspirate the rinse solution for several minutes.
1. Turn off the flame by toggling the **Standby Button** in the flame control window.
1. Close the acetylene tank.
1. Close the air line.
1. Bleed the lines of fuel and air by pressing **Bleed Gases** in the flame control window.
1. Close the software and log out of the computer.
1. Turn off the instrument with the **green power switch** and clean up your work area.

# Troubleshoot

1. *Waste or gas pressure interlock error*: Most likely there is not enough liquid in the waste line to engage the float switch; pour 100-200 mL of water into the waste line.
1. *Buttons greyed out*: Another window is active and blocking the operation; close some windows that you aren't using and try again.
1. *Unable to import sample information*: Make sure the **Define Samples** option is set to *Define All* under the Analysis tab.
