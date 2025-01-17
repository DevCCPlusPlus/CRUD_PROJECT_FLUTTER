# CRUD_PROJECT_FLUTTER
A CRUD PROJECT BASED ON FLUTTER

<h1> A.FILE PICKER WIDGET </h1>
<ul>
<h3><i><ins> Note: File Picker will not work  if Android SDK is not v33 </ins> </i><h3>
<h2>1. Android SDK problem</h2>
<ul>
  <li><h3>1.Go to Flutter SDK extracted location Eg: C:/flutter </h3> </li>
  <img src="https://user-images.githubusercontent.com/38869235/182935505-dd00508a-bc06-4f9b-86f1-2e584174450a.png" width="500" height="200">
  
  <li><h3>2.Next go to flutter→packages </h3> </li>
  <img src="https://user-images.githubusercontent.com/38869235/182935918-6c657b1a-0318-4646-a0de-c44cf3410ddf.png" width="500" height="200">
  
  <li><h3>3.Next go to flutter→packages→tools </h3> </li>
  <img src="https://user-images.githubusercontent.com/38869235/182936283-76bf65f0-775f-4f85-ae2b-dbdc14b8bc06.png" width="500" height="200">
  
  <li><h3>4.Next go to gradle and open the folder </h3> </li>
  <img src="https://user-images.githubusercontent.com/38869235/182936689-2c0555ef-837b-436d-b9ac-d90ada9099de.png" width="500" height="200">
  
  <li><h3>5.Go to flutter.gradle and open it. </h3> </li>
  <img src="https://user-images.githubusercontent.com/38869235/182937037-3e799a28-e124-4caa-b4b5-04288141d5ff.png" width="500" height="200">
  
  <li><h3>6.Change compileSDK = 33 . Save and close.
 </h3> </li>
  <img src="https://user-images.githubusercontent.com/38869235/194891715-a74c59c6-4d40-4c91-8fe3-51226a9a3839.png" width="500" height="200">

</ul>
<h2> 2. Install the file picker from the link: <a href= "https://pub.dev/packages/file_picker"> File Picker Package </a> <h2>
<h2> 3. Give or Allow Permission for read and Write   </a> </h2>
<ul>
  <li><h3> 1. app/src/debug/AndroidManifest.xml </h3> </li>
  <img src="https://user-images.githubusercontent.com/38869235/194903326-44169d57-73ce-4306-92ca-498a0bb29d32.png" width="1000" height="200">
  <li><h3> 2. app/src/main/AndroidManifest.xml </h3> </li>
  <img src="https://user-images.githubusercontent.com/38869235/194903801-03d81837-91ea-4938-8589-81c39b637f7b.png" width="1000" height="200">
  <li><h3> 2. app/src/profile/AndroidManifest.xml </h3> </li>
  <img src="https://user-images.githubusercontent.com/38869235/194904705-1246bb09-e376-4bcc-aa4c-a4cc6318ad4b.png" width="1000" height="200">

</ul>
 <h2> 4. File Picker Use Case   </a> </h2>
  <ul>
    <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master"> A Simple File Picker Use Case </h3> </li>
    <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master2"> Storing an Image file in FireStore Storage of Firebase using File Picker </h3> </li>
  </ul>
  
<h2>5. Then we can now the commands: A. flutter clean , B. flutter pubget , C. flutter run (Better run in Android Mobile Device making USB debug on) </h2>
<h2> 6. The permission / Rules of FireStore will be: </h2>
  <ul>
    <img src="https://user-images.githubusercontent.com/38869235/194953481-ca453b4a-f1ee-4507-ad86-cab0acde9f0b.png" width="1000" height="500">
    <h3><i>Note : As Authorized Person only can upload the pictures in the storage file. </i></h3>
    
  </ul>
  
  <h2>7. RadioButton . </h2>
  <ul>
  <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master3"> RadioButton UseCase and Setting Doc portion of Firebase.</h3> </li>
  <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master4"> Fetching Data using Stream Query Snapshot and Stream Builder.</h3> </li>
  </ul>
  <h2>8. Table . </h2>
  <ul>
  <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master5"> An UseCase of Creation of Table in Flutter.</a></h3> </li>
  <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master6">Fetching Data From Firebase to Table.</a></h3> </li>
  <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master7">Delete Query to Delete Data From Firebase And Table Simultaneously.</a></h3> </li>
  </ul>
  <h2>9. CheckBoxes . </h2>
  <ul>
  <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master8"> An UseCase of CheckBox in Flutter.</a></h3> </li>
  <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master9"> Inserting Data using CheckBox into Firebase .</a></h3> </li>
  <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master10"> Fetching and Displaying the Inserted Data using CheckBox , Firebase and Flutter .</a></h3> </li>
  </ul>
  <h2>10. Data Table . </h2>
  <ul>
  <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master11"> An UseCase of Data Table in Flutter.</a></h3> </li>
  <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master12"> An UseCase of Using List of Map in Data Table in Flutter.</a></h3> </li>
  <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master13"> Fetching Data in DataTable Widget of Flutter from Firebase.</a></h3> </li>
  <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master14"> Delete Query to Delete Data From Firebase And DataTable in Realtime.</a> </h3></li>
  </ul>
  <h2>11. Text Form Field(Same for Text Field) . </h2>
  <ul>
  <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master15"> An UseCase of Text Form Field  in Flutter.</a></h3> </li>
  <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master16"> Inserting Data in FireBase through Text Form Field in Flutter.</a></h3> </li>
 <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master17"> Fetching The Inserted Data from FireBase in Flutter.</a></h3></li>
  </ul>
 <h2>12. FutureBuilder </h2>
 <ul>
  <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master18"> Future Builder Fetching All the DOCIDS from Firebase.</a></h3> </li>
   <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master20">Using Future Builder Fetching Image From FireStore Storage.</a></h3> </li>
  </ul>
  <h2>12. Incrementing Document(User Defined)  even if Page reloads from start </h2>
  <ul>
  <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master19">  Incrementing Document(User Defined) of FireBase even if Page reloads from start.</a></h3> </li>
  </ul>
 
</ul>

<h1> B.CRUD PROJECT (With Table Widget) </h1>
  <ul>
    <h3> 1. Parts Of the Project </h3>
    <ul>
  <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master21"> 1.  Building the Student Details Screen.</a></h3> </li>
  <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master22"> 2. INSERTING DATA INTO FIREBASE(With Snackbar Message).</a></h3> </li>
  <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master23"> 3. Viewing Saved FireBase Data As A TABLE and Fetching Data Individually.</a></h3> </li>
  <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master24"> 4. Edit Individual's Data and Update the Field in Database .</a></h3> </li>
 <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master25"> 5. Delete Data From Firebase Storage and FireStore Database .</a></h3> </li>
  <li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master26"> 6. Update Profile Pic .</a></h3> </li>
  </ul>
<h3> 2. Final Build </h3>
<ul>
<li><h3> <a href="https://github.com/AvinandanBose/firebasefirestoreproj1/tree/master27"> Final BuildCRUD PROJECT (With Table Widget) .</a></h3> </li>
</ul>
  </ul>

 
  </ul>
