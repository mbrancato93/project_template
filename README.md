<h2>C Program Project Template</h1>

<p>
  Simple project template for C programs to quickly get started on a new project. </br>
  <!--</br> -->
  
  Project comes with Unit testing support through the check framework*.</br>
  <!--</br> -->
  
  Memory leak checking support through valgrind*</br>
  <!--</br> -->
  
  
  </br></br>
    * Template untested with locally installed versions of Check framework and Valgrind. Check normally installed in 'libs' folder, Valgrind normally installed in      'progs' folder. These were not involved due to licensing concerns. 
  
</p>

<h3>Notes:</h3>
<p>
  <ul>
    <li>To enable gdb debugging support within unit tests, environment variable 'CK_FORK=no' should be set then cmake re-run.</li>
    <li>Compile with 'cmake -DCMAKE_BUILD_TYPE=[Debug, Release] . && make'</li>
  </ul>
  
</p>

<h3>TODO:</h3>
<ol>
  <li>Add support for locally installed Check framework </li>
  <li>Add support for locally installed Valgrind </li>
  <li>Add prompted install of latest version of Check, Valgrind into appropriate locations </li>
</ol>
