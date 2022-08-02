# college website
 This is a mern stack project which i have completed during my summer Internship.<br /> 
 
 Steps to run this application:<br /> 
 1.Download this zip folder / clone this repository into your local pc.<br /> 
2.For running this application you should have your mongodb database connected with this application.<br /> 
![image](https://user-images.githubusercontent.com/71025467/182306608-656d60a4-c979-45a1-afa6-8515373ebbcf.png)<br/>
3.You can store the required MONGO_URL,MONGOPASSWORD , other secret keys and links in .env file.<br /> 
![image](https://user-images.githubusercontent.com/71025467/182308462-4568d7af-6552-4133-9900-60f7e9255ec4.png)<br />
4.Here cloudinary is used for storing profile photos of admin,students and faculty members.<br />
5.Open this college website project using some editor having required setup to run react.js and node.js applications(eg.vscode with required extensions and node.js installed in your computer).<br />
6.Open two different terminals.<br />
   b)One for running server.<br /> 
     1.cd server<br />
     2.npm start<br />
   a)Other terminal for running client.<br />
     1.cd client<br />
     2.npm start<br />
7.We can now see student and faculty login page.<br />
![student faculty login](https://user-images.githubusercontent.com/71025467/182311046-c15d19dd-0b3a-4cd6-a022-46e7b74698e5.png)<br />
8.Go to admin login page.<br />
http://localhost:3000/adminLogin<br />
We have hard coded this admin.<br />
ROOT_ADMIN_REGNO=ADM0001<br />
ROOT_ADMIN_PASSWORD=01-01-2000<br />
This admin will be used to add other admin,student,faculty in our database.<br />
9.Now we can login to admin using Root_admin_regno,Root_admin_password.<br/>
![admin login](https://user-images.githubusercontent.com/71025467/182324804-e58312fa-8ee5-4e54-9881-3d5f7698b1b3.png)<br/>
Our admin page has the following features:<br/>
a)Admin profile page:</br>
![adminprofile](https://user-images.githubusercontent.com/71025467/182325368-a0c84a3c-bf28-4bf3-beff-78af26662273.png)<br/>
b)Add faculty page:<br/>
![adminaddfaculty](https://user-images.githubusercontent.com/71025467/182325542-a82480b7-db51-45cb-acad-60dbf162b5c2.png)</br>
c)Add student page:<br/>
![adminaddstudent](https://user-images.githubusercontent.com/71025467/182325717-a9c3755e-f124-4d7a-994d-92baf582335c.png)<br/>
d)Add subject page:<br/>
![admin add subject](https://user-images.githubusercontent.com/71025467/182325866-d0dafd81-7c92-4268-b887-4f03f1a5dd90.png)<br/>
e)Add admin page:<br/>
![admin add admin](https://user-images.githubusercontent.com/71025467/182326117-675caa9e-33f6-4406-b60c-6c67c664d18d.png)<br/>
f)Our faculties page:From this page we can see all the faculties present in our database.<br/>
 ![admin can see all faculties](https://user-images.githubusercontent.com/71025467/182326472-7e7914a5-480f-439e-9cbe-68e40d4b5177.png)<br/>
g)All students page:From here admin can see students present in various department and year.<br/>
![admin can see all students in database](https://user-images.githubusercontent.com/71025467/182326718-164f308f-8ebf-4e23-989c-9bfc8174c197.png)<br/>
h)All subjects page:From here admin can see all the subjects present in various department and year.<br/>
![admin can see all subjects in database](https://user-images.githubusercontent.com/71025467/182326911-6f2746d1-2fdb-4e03-b161-8e476f0ad299.png)<br/>
Our Faculty page has the following features:<br/>
a)Faculty Profile Page:Faculty can see his information stored in database from here.<br/>
![faculty profile](https://user-images.githubusercontent.com/71025467/182327543-45dd68e2-65a9-4918-9026-dc9fc0346715.png)<br/>
b)Update Profile page:From here faculty can update information such as profile picture,contact number ,Aadhar card number.<br/>
![update faculty profile picture](https://user-images.githubusercontent.com/71025467/182327856-68474103-a1a4-4b4d-960b-f8cc205b533a.png)<br/>
c)Attendance Faculty page:From here faculty can mark attendance to their department students.<br/>
![faculty can mark attendance to only its department students](https://user-images.githubusercontent.com/71025467/182328140-f1fcf18d-5602-40ce-b8a9-09a8c23e0134.png)<br/>
d)Uplaod marks page:From here faculty can upload marks of their subject to the student of various year and department.<br/>
![faculty can give marks to their department students from different sections](https://user-images.githubusercontent.com/71025467/182328584-dd4d9443-d9cc-4518-a90b-7c22165c3e0d.png)<br/>
e)Update password page:From this page faculties can change their password ,by default password is set to date of birth.<br/>
![faculty can update password ,by default password is dob](https://user-images.githubusercontent.com/71025467/182329467-59b468a8-ee00-45d8-a171-140c5c1f8d43.png)<br/>
Our Student page has the following features:<br/>
a)Home page:This is profile page for the student,it has all the information related to student in database.<br/>
![student profile ](https://user-images.githubusercontent.com/71025467/182330115-df793070-7b92-4cd6-a784-d0690b54502c.png)<br/>
b)Update profile page:From here student can update his information such as profile picture,contact number ,aadhar number etc<br/>
![student can update profile picture](https://user-images.githubusercontent.com/71025467/182330510-7ca774e1-5ff6-4d74-8ccd-7e071b754e42.png)<br/>
c)Academic section has three pages stored in dropdown menu:<br>
    A)Test Performance page:This page will contain the result of student for various subjects.<br/>
    ![student can see test performance in academics test performance tab](https://user-images.githubusercontent.com/71025467/182331474-43b328fa-6fc7-43b1-8e0e-b1e87b13c7b7.png)<br/>
    B)Attendance page: Here student can see his attendence,attendence percentage for in various subjects.<br/>
    ![students can see their attendance in academic attendance tab](https://user-images.githubusercontent.com/71025467/182331579-9a06446f-5403-42da-8b4e-fc760159ac7f.png)<br/>
    C)Get all subjects page: Here student can his all the subjects in his curriculam.<br/>
    ![students can see subjects in their curriculam](https://user-images.githubusercontent.com/71025467/182331864-976369ea-68b8-42ff-a77e-720accad6dc6.png)<br/>
d)Update password page:From here students can update their password ,by default it is set to date of birth.<br/>
![student can update their password](https://user-images.githubusercontent.com/71025467/182332258-4f0325d3-ce7a-469b-bb3d-36441752c5c0.png)<br/>

10).In this project we are using mongodb database.<br/>
![database](https://user-images.githubusercontent.com/71025467/182332775-8b969c60-99a4-41e6-b0fc-d8f8489835c7.png)<br/>

   
