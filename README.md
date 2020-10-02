# parkingLot

<h2> How to run : </h2>
<ul>
  <li> Download this main.cpp file. </li>
  <li> Create 2 text files namely -> input.txt and output.txt in same directory as of main.cpp </li>
  <li> Provide test case in input.txt file </li>
  <li> Run main.cpp from terminal or any IDE </li>
  <li> See the result/output in output.txt </li>
</ul>
<br>
<h3> To run on mac : </h3>
Compile using Clang
<code> $ g++ -o main main.cpp </code> <br>
Run the binary executable: <br>
<code> $ ./main </code>
<br> <br>
<h3> To run on Unix machine :</h3> <br>
In case of Ubuntu it doesn't have C++ compiler by default. You need to install it by below command: <br>

<code> sudo apt-get install g++ </code> <br>
Now you can compile your programs like this: <br>

<code> g++ main.cpp -o output  </code> <br>
Now you can run the same with below command: <br>

<code> ./output </code> <br>
Troubleshoting: By default g++ creates executable output. If in case you have permission denied error then try command: <br>

<code> chmod u+x OutputFile </code> <br>
<h3> Sample Input : </h3> <br>

Create_parking_lot 6 <br>
Park KA-01-HH-1234 driver_age 21 <br>
Park PB-01-HH-1234 driver_age 21 <br>
Slot_numbers_for_driver_of_age 21 <br>
Park PB-01-TG-2341 driver_age 40 <br>
Slot_number_for_car_with_number PB-01-HH-1234 <br>
Leave 2  <br>
Park HR-29-TG-3098 driver_age 39 <br>
Vehicle_registration_number_for_driver_of_age 18 <br>
