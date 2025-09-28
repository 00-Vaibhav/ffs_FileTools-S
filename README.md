# ffs_File Tools

## **Find it. Fix it. Submit it!**

**ffs_File Tools** is a simple Windows application that helps validate a Drawing Register/ MIDP (Excel/CSV) data against folder directories for relevant file exports, helping ensure Ensure all project files are present before delivery.

---

![01](https://github.com/user-attachments/assets/5ef257ef-f2c8-42c5-a9e7-80279edf3515)

## **Key Features**

### 📊 Multi-Format Support
- **Excel Files**: .xlsx, .xlsm, .xltx support
- **CSV Files**: Universal compatibility
- **Smart Worksheet Selection**: Choose specific Excel worksheets

### 🔍 **Advanced File Matching**
- **Flexible Column Mapping**: Select any column containing file names
- **Intelligent Filtering**: Filter data by column values
- **Case-Sensitive Options**: Precise matching control
- **Whole Word Matching**: Avoid partial matches
- **Subdirectory Scanning**: Deep folder analysis

### 📈 **Results**
- **Real-Time Preview**: See your data before processing
- **Detailed Reports**: Comprehensive validation results
- **Excel/CSV Export**: Share results with your team

---

## 🛠️ **How It Works**

### File Matching
Access the file matching functionality through the File Operations dialog:

1. **Select Data Source**: Choose an Excel or CSV file containing file names to validate
2. **Select Target Folder**: Choose the folder to check for the existence of files
3. **Configure Options**:
   - Select the column containing file names from your Excel/CSV
   - Optionally set up filtering by column and value
   - Choose matching options (case sensitivity, whole word matching, subdirectories)
4. **Run Check**: Click "Run Check" to perform the validation
   
   ![02](https://github.com/user-attachments/assets/cbdad866-c678-4b68-8873-1b3dc13f9f8e)
   
6. **Review Results**: View detailed results showing which files exist and which are missing
7. **Export Results**: Save results to Excel for further analysis
   
   ![03](https://github.com/user-attachments/assets/ebb4c8b6-fe91-471f-ab74-5414c7d6ff7f)


### File Renaming
Access the file renaming functionality through the File Operations dialog:

1. **Select Folder**: Choose the folder containing files to rename
2. **Configure Renaming Options**:
   - **Text Replacement**: Replace specific text in filenames with new text
   - **Add/Remove Prefix**: Add or toggle a prefix on filenames
   - **Add/Remove Suffix**: Add or toggle a suffix on filenames
   - **Case Conversion**: Apply various case transformations:
     - Uppercase/Lowercase
     - Sentence Case, Title Case
     - camelCase, PascalCase
     - snake_case, Kebab-Case
   - **Target Directory**: Choose to rename files in main folder only, all subdirectories, or specific subdirectories
3. **Preview Changes**: Review all proposed changes before execution
4. **Selective Execution**: Choose which files to rename using checkboxes
5. **Execute Renames**: Apply the selected changes with comprehensive error handling
   
   ![04](https://github.com/user-attachments/assets/c75023b3-cdda-4546-96bc-af461c83c904)
   
---

## 💻 **System Requirements**

### Prerequisites
- **Windows 10/11** (64-bit)
- **.NET 8.0 Runtime** (free download from Microsoft)
- **Minimum 4GB RAM** (8GB recommended for large datasets)

### Uses
- **ClosedXML**: For Excel file reading (.xlsx, .xlsm, .xltx)
- **Ookii.Dialogs.Wpf**: For native Windows file/folder dialogs
- **WPF**: For the user interface

## Disclaimer

**This is a testing release.** The author bears no responsibility for any loss, damage, or harm that may result from the use of this software. Use at your own risk.
