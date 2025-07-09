# Printing Instructions:
# Getting Started: 3D Printing with Cura and .OBJ Files

## 1. What is Cura?
Cura is free slicing software developed by Ultimaker.  
A slicer takes a 3D model and converts it into instructions a 3D printer understands, called **G-code**.  
Cura is popular because it is easy to use, compatible with most desktop 3D printers, and supports various file types.

## 2. What is a .OBJ File?
A `.obj` file is a widely used 3D model format that stores the geometry of an object.  
It may also include color and texture data. These files are created in 3D modeling programs like Blender, Tinkercad, or Fusion 360 and can be imported into slicing software like Cura for printing.

---

## How to Download a File from GitHub

To download a file (such as a `.obj` model or `.md` instruction file) from a GitHub repository:

1. Navigate to the GitHub repository (or folder) containing the file.
2. Click on the file name you want to download.
3. One you are on the file page click the three dots (...) in the upper righthand corner of the page and select **"Download"**.
4. The file should appear in the Downloads folder on your computer. 

To download entire repositories or folders:
1. Go to the repository’s main page.
2. Click the green **“Code”** button.
3. Select **“Download ZIP”** to download the whole project as a compressed file.

---

## Setting Up and Using Cura

### 3. Download and Install Cura
1. Visit the official Cura website: [https://ultimaker.com/software/ultimaker-cura](https://ultimaker.com/software/ultimaker-cura)
2. Download the version that matches your operating system (Windows, macOS, or Linux).
3. Install Cura by following the installation instructions.

### 4. Set Up Your Printer
1. Open Cura.
2. The first time you launch Cura, you’ll be prompted to add a printer.
3. Select your printer model from the list.  
   If your exact model is missing, choose a similar one and manually adjust build volume and settings.
4. Verify that the build plate size and other printer settings are correct.

---

## Importing and Preparing .OBJ Files

### 5. Import the .OBJ File
1. After you have downloaded the .obj files from github, click **“Open File”** in the toolbar or drag and drop your `.obj` file into the Cura window.
2. The model will appear on the virtual build plate.

### 6. Format and Position the Model
- **Move**: Use the move tool to position the model within the print area.
- **Rotate**: Adjust the orientation so the flattest side is on the build plate.
- **Scale**: Resize the model using the scale tool. Lock axes to scale uniformly.
- Right-click the model and use **“Lay Flat”** or **“Center Selected Model”** to quickly adjust placement.

---

## Slicing and Exporting

### 7. Configure Print Settings
In the right-hand panel, adjust key settings:
- **Layer height** (e.g., 0.2 mm for standard prints)
- **Infill density** (e.g., 15%)
- **Supports** (enable if your model has overhangs)
- **Build plate adhesion** (e.g., add a brim or raft)

### 8. Slice the Model
- Click the **“Slice”** button at the bottom-right.
- Cura will generate the G-code and display estimated print time and material use.

### 9. Export the G-code
- Click **“Save to File”** or **“Save to Removable Drive”** (if using an SD card or USB stick).
- Transfer the storage device to your 3D printer and start your print.

For more information on how to use Cura, please visit: [https://ultimaker.com/learn/how-to-use-a-3d-printer/](https://ultimaker.com/learn/how-to-use-a-3d-printer/)
