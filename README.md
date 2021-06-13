# Customize weapons
## pistol
- Ko nên làm việc với assembly.xml vì nó rất intricate(rối ren), hãy dùng bên thứ 3
- Xpath coi chừng lấy sai, phải để chuột đúng vị trí giữa Clipsize
- thay đạn nằm trong weaponcomponents.meta , ko phải weapons.meta
- khi dùng phần mềm thứ 3, mọi path hay archive hay rpf hay directory gốc lun lấy ở folder orignal của game, đừng lấy path trong mod folder vì lúc mới cài lại game sẽ ko có mod folder
- khi dùng oiv để cài oiv package, lun cài ở mod folder (vì nó ko ghi đè giữ liệu vào thư mục game. mà sẽ tạo 1 cái trong mod)
- Trang lấy Xml path: https://xmltoolbox.appspot.com/xpath_generator.html
- Openiv nói gì về cách tạo .OIV ? : https://github.com/OpenIV-Team/OpenIV-PackageFormat/blob/master/specification/versions/2.1.md
- lỗi nhẹ khi ClipSize[@value="8"], bỏ số 8 đi ok
