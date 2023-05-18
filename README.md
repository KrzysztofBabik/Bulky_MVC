- <b>*BulkyWeb*</b> is an ASP .NET Core MVC application.
- <b>*BulkyWebRazor_Temp*</b> is a clone of BulkyWeb, but uses RazorPages.
---
<b>How to configure project:</b>
1. Make sure your database server has a name like in *ConnectionString - DefaultConnection* in *...\appsettings.json*
2. Delete *Migrations* folder in *Bulky.DataAccess* project.
3. In the *Package Manager Console* choose *Default project* to *Bulky.DataAccess* and type <code>add-migration AddCategoryToDbAndSeedTable</code>
4. Then type <code>update-database</code>
---
<b>How to configure project (BulkyWebRazor_Temp):</b>
1. Make sure your database server has a name like in *ConnectionString - DefaultConnection* in *...\appsettings.json*
2. Delete *Migrations* folder.
3. In the *Package Manager Console* type <code>add-migration AddCategoryToDbAndSeedTable</code>
4. Then type <code>update-database</code>
---
<b>Useful sites:</b>
- *[Bootswatch](https://bootswatch.com/)*
- *[Bootstrap icons](https://icons.getbootstrap.com/)*
- *[Toastr](https://codeseven.github.io/toastr/)*
