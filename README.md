# Update upload files

ატვირთეთ ეს სამი ფაილი public hosting-ზე ერთსა და იმავე release საქაღალდეში:

- `NovacioMedicalExportSetup.exe`
- `MedicalPatientExport_Portable.zip`
- `update_manifest_latest.json`

`update_manifest_latest.json`-ში `installer_url` უნდა მიუთითებდეს public installer URL-ს.
აპი ინსტალერს გაუშვებს მხოლოდ მაშინ, თუ sha256 ზუსტად დაემთხვევა.
