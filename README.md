# Blender to Meta Horizon Worlds Exporter  

A Blender add-on that prepares and exports 3D models for **Horizon Worlds** (HW).  
This tool simplifies the process of optimizing, baking textures, and exporting FBX files. This isn't meant for experts. It's meant for people who are just wanting to get some objects and textures into HW very quickly.

I will fully admit if you want to get fancy, you're still going to have to take the time learn the true in-and-outs of how Blender and HW need to work together, to get the best results. This is just something to let you hit the ground running, and get some Tri-Mesh into your world(s) very easily. What it exports are not necessarily the best they could be.

---

## **Features**
✔️ **One-Click Export** – Automates the entire export process.  
✔️ **Texture Baking** – Generates properly named **_BR** and **_MEO** textures.  
✔️ **Decimation Tool** – Reduce vertex count using a slider.  
✔️ **UV Smart Unwrap** – Automatically creates UVs if missing.  
✔️ **FBX Export** – Ensures correct format for Horizon Worlds.  

---

Note: Knowing some of the limitations that HW has when importing is a must before you even start. How many files can be used per object, files sizes, etc. Otherwise you'll be shouting at your computer. I'm not stating numbers now, because things might change at a later date.

---

## **Installation**
1. **Download the add-on**  
   - Click **Code** → **Download ZIP** on GitHub to a place an your computer you can find easily later.    
   - Do *NOT* extract the zip file.
   
2. **Install in Blender**  
   - Open **Blender** → **Edit** → **Preferences** → **Add-ons**.  
   - Click **Install** and select the **ZIP file** you've just saved.  
   - Enable **Horizon Worlds Exporter** in the add-ons list. 
   - Close Blender and re-open it again. (Otherwise it may not show for an object you own up directly afterwards)   

---

## **How to Use**
### **1. Select Your Object**
- Ensure your object is a **mesh** (NURBS, curves, and text objects must be converted).  
- If your object consists of multiple parts, select one part, then press `A` to select everything.  

### **2. Open the Export Panel**
- Press 'N' to open the **Side Panel** in the 3D View.  
- Navigate to the **Horizon Export** tab.  

### **3. Adjust Settings (Optional)**
- **Decimate Ratio** – Adjust to reduce vertices count.  
- **Apply Decimation** – Manually apply decimation if needed.  

### **4. Export**
- Click **Export FBX** – The add-on will:  
  - **Apply transforms** (scale, rotation, location)  
  - **Apply modifiers**  
  - **Generate UVs** (if missing)  
  - **Bake textures** (_BR and _MEO)  
  - **Export the FBX file**  

### **5. Locate Your Files**
- Your exported files will be in:  <Blender_Project_Folder> / <Project_Name>_HW /          --- Where ever your project is saved, a new folder will appear there with _HW at the end.
  - This folder will contain:  
  - The **FBX file**  
  - The **baked textures** ('_BR.png' and '_MEO.png')  

---

## ☕ Support My Work
If you like this project, consider buying me a coffee!

[![Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/fairfight14)


---

## **Troubleshooting**
- **No textures are being created?**
  - Ensure your model has materials with image textures.  
  - Make sure materials are assigned properly.  

- **Export button is missing?**
  - Check that you have a valid mesh selected.
  - Ensure the add-on is enabled in **Blender Preferences**.  

- **Decimation doesn’t reduce the vertex count?**
  - Adjust the **Decimate Ratio** before exporting.  
  - Manually apply decimation if needed.  

---

## **Credits**
**Author:** FairFight14  
**Version:** 1.0.1  
**License:** GNU GPL v3.0

---

**Blender and Meta Horizon Worlds hold their full rights to their software and names, all I did was write a simple add-on. You use this add-on at your own risk.*
