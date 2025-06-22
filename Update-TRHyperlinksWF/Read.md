# 🔗 Update TR-No. with Matching File Hyperlinks

## 🧾 Description
This Power Automate flow updates the "Hyperlink" field in the "Technical Reports" SharePoint list by searching for a matching file in the `RnD/07-Technial-Reports` folder and inserting the direct file link.

## 📂 Flow Components
- Trigger: Manual or Scheduled
- Get Items from SharePoint list
- Get Files (properties only) from SharePoint folder
- Filter to match file name with TR-No. (Title field)
- Update Hyperlink column with direct file link

## 🗂 SharePoint Setup
| Component        | Name                     |
|------------------|---------------------------|
| List             | Technical Reports         |
| Column (TR-No.)  | Title                     |
| Column (Link)    | Hyperlink (type: Hyperlink or Picture) |
| Document Library | RnD/07-Technial-Reports   |

## 📦 How to Use
1. Import `UpdateTRHyperlinks.zip` into Power Automate.
2. Reconnect SharePoint connections during import.
3. Update folder paths or column names if needed.

## 🧑‍💻 Author
Manish Parashar
