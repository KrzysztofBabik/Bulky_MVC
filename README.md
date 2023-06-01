- <b>*BulkyWeb*</b> is an ASP .NET Core MVC application where you can register and (depending on your account role) buy things, manage your profile or manage whole things in the store, such as products and categories.
- <b>*BulkyWebRazor_Temp*</b> is a clone of old version of BulkyWeb, but uses RazorPages.
---
<b>How to configure project:</b>
1. Make sure your database server has a name like in *ConnectionString - DefaultConnection* in *...\appsettings.json*
2. Delete *Migrations* folder in *Bulky.DataAccess* project.
3. In the *Package Manager Console* choose *Default project* to *Bulky.DataAccess* and type <code>add-migration InitDb</code>
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
- *[DataTables](https://datatables.net/manual/data/)*
- *[SweetAlert](https://sweetalert2.github.io/)*
