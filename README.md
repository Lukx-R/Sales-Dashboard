# Sales & Revenue dashboard using Microsoft Power BI

## This dashboard;

The Sales and Revenue Power BI dashboard visualizes an organization's sales performance and revenue metrics, focusing on product shipments. It enables interactive analysis, empowering informed decision-making.

##  Visualizations;

### First page

![First Page](https://github.com/Lukx-R/Sales-Dashboard/assets/140380009/d7a1b8c6-00b0-4fce-92d8-7fd672af518f)

### Second page

![Second Page](https://github.com/Lukx-R/Sales-Dashboard/assets/140380009/50cafbe4-0afa-453b-b09e-298e147d54c8)

Here you can see there's an error in one visual due to a different visualization created using a Python script. I used matplotlib and seaborn libraries to plot a swarmplot in this dashboard. 
To view this visualization, follow these steps;

#### Python script:
```python
import seaborn as sns
import matplotlib.pyplot as plt
sns.set()
sns.swarmplot(x="Category", y="Revenue",  data = dataset)
plt.xticks(rotation=75, fontsize = 12)
plt.show()
```

1. Go to Options: **File >> Options & settings >> Options**
2. Select Python scripting option.
3. Choose the Python directory you are using.

In my case, I selected the Anaconda directory path.

![Py Setting](https://github.com/Lukx-R/Sales-Dashboard/assets/140380009/9e5b98f6-6eef-4f05-9090-098f9ce448f3)

4. Open Anaconda Prompt from the Windows search (if you don't have Anaconda Navigator, download it [here](https://www.anaconda.com/download).)
5. Copy the path of the Power BI dashboard file, paste it in the Anaconda Prompt, and press Enter.

![Anaconda Path](https://github.com/Lukx-R/Sales-Dashboard/assets/140380009/2a5c3307-85a7-4dc3-bae7-ed0795059904)

6. You'll receive a prompt message to enable the script visual; click **Enable**

![Enable](https://github.com/Lukx-R/Sales-Dashboard/assets/140380009/83bf35b3-d135-47d2-b57c-3ab4e1228329)

Then you will then see the swarmplot generated by the Python script.;

![Python chart](https://github.com/Lukx-R/Sales-Dashboard/assets/140380009/8899dbaf-d0e4-4951-8893-1f1de32cedfc)

You have alternatives to run Python scripts in Power BI without using Anaconda Prompt or downloading Anaconda Navigator. You can choose any of these methods;

* https://learn.microsoft.com/en-us/power-bi/connect-data/desktop-python-scripts
* https://learn.microsoft.com/en-us/power-bi/connect-data/desktop-python-visuals?source=recommendations
* https://www.youtube.com/watch?v=3_DOF_qjguA

## Power BI Desktop installation

1. **Download Power BI Desktop:** <br> 
Visit the official Microsoft Power BI [website](https://www.microsoft.com/en-us/download/details.aspx?id=58494) to download the installer.
2. **Select the Appropriate Version:** <br>
Choose the version of Power BI Desktop that matches your operating system. Typically, you'll have options for 32-bit and 64-bit versions. If you are unsure, check your computer's system properties to see if it's a 32-bit or 64-bit system.
3. **Run the Installer:** <br>
After downloading the installer, run it by double-clicking on the downloaded file. If prompted by User Account Control (UAC), click "Yes" to allow the installer to make changes to your computer.
