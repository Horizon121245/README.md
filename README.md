# ♾️ INFINITY Suite for Autodesk® Revit® - Official Help Guide

Welcome to the official documentation for the **INFINITY Suite** by Horizon BIM Services. This guide provides detailed instructions on how to use every tool and sub-feature within the INFINITY Ribbon panel to automate your workflows, protect your project data, and manage your Revit deliverables.

---

## 👤 1. User Account
**Manage your identity, license, and subscription status.**
* **Overview:** The User Account manager is your central hub for activating and maintaining your INFINITY license.
* **Features:**
  * **Status Dashboard:** Instantly view if your license is Trial, Pro, or in an Offline Grace Period.
  * **Offline Mode:** INFINITY supports offline work for up to 7 days, allowing you to stay productive even without an internet connection.
  * **License Details:** Displays your exact Expiration Date, Days Remaining, and secure Machine ID.

## 🚀 2. Script Runner
**Execute Python and C# scripts instantly without external editors.**
* **Overview:** A powerful, built-in IDE that allows BIM Managers and developers to test and run code directly inside the active Revit model.
* **Features:**
  * **Multi-Language Support:** Switch seamlessly between the **Python (IronPython 2.7)** tab and the **C# (Roslyn)** tab.
  * **Integrated Console:** View print statements, execution results, and error logs directly in the bottom output window.
  * **Safety First:** Includes a quick "Save Project" button to protect your model before running experimental, unsaved code.

## 💾 3. Auto Save
**Protect your project from unexpected crashes with smart saving.**
* **Overview:** Standard Revit only provides reminders. INFINITY Auto Save actively manages your file saves.
* **Settings:**
  * **Save Interval:** Define exactly how often the system saves (e.g., every 30 minutes).
  * **Scope:** Choose to save only the *Active Document* or *All Open Documents* simultaneously.
* **Notification Modes:**
  * **Show Reminder Popup:** Prompts you for permission before saving so it doesn't interrupt a heavy modeling task.
  * **Silent Mode:** Seamlessly saves your document in the background without any popups or interruptions.

## ⏱️ 4. Time Summary
**Automatically track your active, billable hours inside Revit.**
* **Overview:** A passive time-tracker that monitors your active modeling time.
* **Features:**
  * **Smart Idle Detection:** Configure the "Idle Limit" (e.g., 5 minutes). If your mouse doesn't move, INFINITY pauses the timer so you don't track inaccurate "away" time.
  * **Project Filtering:** Switch between different project logs to see exactly how much time was spent on each specific Revit file.
  * **Interactive Charts:** View a graphical breakdown of your last 7 or 30 days of active work.

## 🖨️ 5. Print Manager *(Revit 2022+)*
**Batch export your documentation sets with advanced naming rules.**
* **Overview:** A highly customizable engine for exporting Views and Sheets.
* **1. Selection & Sorting:** Filter your list to show only Sheets or Views, and sort them naturally, alphabetically, or by Browser Organization.
* **2. Export Modes:**
  * **PDF (Native Exporter):** Utilize Revit's native PDF engine. Includes settings for Paper Size (Auto-detect from Titleblock), Zoom, Orientation, Color Mode, and DPI Quality.
  * **CAD (DWG):** Export drawing files with specific AutoCAD version years (2013, 2018) and choose whether to export views as external references (XRefs).
* **3. Visibility Overrides:** Clean up your prints by toggling off Reference Planes, Unreferenced Tags, Scope Boxes, and Crop Boundaries directly from the export window.
* **4. File Output & Naming:** Choose to combine all sheets into one PDF, or export separate files using smart naming rules (e.g., `[Prefix] - [SheetNumber] - [SheetName]`).

## 📄 6. Sheet Manager
**Automate sheet creation, renumbering, and project cleanup.**
* **Overview:** The ultimate tool for handling massive documentation sets, divided into five powerful tabs:
  * **1. Renumber:** Select a range of existing sheets (e.g., 101 to 150) and instantly apply new prefixes, suffixes, and sequential starting numbers.
  * **2. Create from Excel/CSV:** Download our standard template, fill it out with hundreds of sheet names/numbers, and import it to generate all sheets instantly using a selected Title Block.
  * **3. Find & Replace:** Search across all sheet names/numbers or views and instantly preview and apply text replacements.
  * **4. Create From Views:** Select multiple unplaced views from a checklist and instantly generate individual sheets for each of them.
  * **5. Cleanup:** Keep your project healthy. Automatically scan for and delete unplaced views, completely empty sheets, or views containing specific "trash" text (like "copy" or "draft").

## ☁️ 7. Revision Manager
**Control revisions across your entire project from one window.**
* **Overview:** A bulk-management tool for Revit's native revision system, separated into two main tabs:
  * **1. Assign Revisions:** The top table lists every sheet; the bottom lists your project's revisions. Check 50 sheets, check "Revision 1", and click **ADD** to instantly apply that revision cloud to all 50 title blocks at once.
  * **2. Create / Import (CSV):** Create single revisions by filling out the Date, Description, and Issued To fields, or use the CSV importer to generate a massive list of project revisions in seconds.

## 🎯 8. Selection Manager
**Save, manage, and retrieve complex element selections.**
* **Overview:** Stop re-selecting the same complex groups of elements every time you change views.
* **How to use:** Manually select any group of elements in your Revit model. Open the Selection Manager and click **Save Current**. The next time you need those elements, simply double-click the saved name in your list, and INFINITY will instantly highlight and select them for you.

## 🔄 9. Check Updates
**Keep your software optimized and up to date.**
* **Overview:** A quick ping to the servers to ensure you have the latest tools.
* **How to use:** Click the button to securely check the Autodesk App Store for newer versions of the INFINITY Suite.

---

## 💻 System Requirements
* **Supported Software:** Autodesk® Revit® 2022, 2023, 2024, 2025, and 2026. 
* **Note:** The native PDF Print Manager tool requires Revit 2022 or newer to function.
* **Operating System:** Windows 10 / Windows 11 (64-bit).
* **Internet:** Required for initial license activation and periodic bi-weekly verification.

## 📥 Installation & Uninstallation

**To Install the Plugin:**
1. Save your work and close all active sessions of Autodesk® Revit®.
2. Run the downloaded `INFINITY_Suite_Setup.exe` file.
3. Follow the on-screen prompts. (Note: Administrator privileges are required to install the necessary files into Revit's Add-In folder).
4. Restart Revit. The **INFINITY** tab will automatically appear in your Ribbon.

**To Uninstall the Plugin:**
1. Close all active sessions of Revit.
2. Open Windows **Settings** > **Apps** > **Installed Apps** (or Control Panel > Programs and Features).
3. Scroll down or search for **INFINITY Suite**.
4. Click **Uninstall** and follow the prompts to completely remove the plugin and its associated files from your machine.

---

### 📩 Need Additional Support?
If you encounter any issues, need help with licensing, or want to request custom API development for your firm, please reach out to us:

* **Website:** [www.HorizonBimServices.com](https://www.HorizonBimServices.com)
* **Email:** Support@HorizonBimServices.com

*© 2026 Horizon BIM Services. All rights reserved.*
