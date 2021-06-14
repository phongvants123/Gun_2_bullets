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
- mặc định game vs mod: 
- +các loại súng cùng type sẽ phát ra âm thanh hết đạn giống nhau. Vậy nên mod manual reload cũng phát ra âm thanh vậy tuy nhiên audio đã được thay đổi đi to hơn
- +hết đạn hoàn toàn sẽ có tiếng chữi, hết đạn magazine thì ko có  . mod manual hết đạn hoàn toàn chỉ có tiếng chữi sau khi được đổi súng, tiếng chửi này là dư âm của cây súng ko đạn cũ (-riêng các loại lựu đạn cầm nắm bên type grenade thì lại ko có, nhưng fire extinguisher và tất cả  thì có) ( tạo nên âm thanh rất hay lúc đổi súng mới cần phát ra)
- +hết đạn hoàn toàn súng tự động đổi, Mod manual reload hết đạn "hoàn toàn" súng cũng tự đổi . cả 2 đều đúng ngay cả khi bạn giữ chuột
- +mod có cái hay là nếu hết magazine thì bạn có 2 options. Hoạc giữ chuột để cầm cây súng đó típ + thả loose để súng tự thu về
