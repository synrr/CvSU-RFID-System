System-Implementation-Set 1

Codings

    1. Reading Input
        * Create a void method that will store data from a file. It's preffered that the file will be stored in an
          ArrayList, rather than an array. But if it's an array, it could be 2 Dimensional having 1024 by 1024 size.
          
          - For now, use FileReader to read files. It's supposed to use Serial Ports and Databases, but we don't have something to
            practice that with.
          - There should be an Array/ArrayList to store hexadecimals IDs.
          - There should be an Array/ArrayList to store students' Full Name.
          - There should be an Array/ArrayList to store students' Student Number.

        2. Create a boolean method that will read 2 strings: A string that is a hexadecimal, and a string that is a 
          student number. We'll hardcode for now. Feel free to name the method whatever you want (like checkValidation)

          If the hexadecimal is 0x0 and the student number is 000000000, return True. Otherwise, return  false.

          This method will be changed to read databases later.

        3. Create a method that will read a String, which holds the value of a student number. For now, if the length of
          the student number is 9, return True, otherwise, return False.

        4. Create a method that will read a String, which holds the value of a Hexadecimal. If the input is a valid
          hexadecimal (Starting with 0x, and with each character are strictly within 0-F (0-9, A-F) return true,
          otherwise return false.

        5. Create a method that will read three strings: the last name, the first name, and the middle initial.

          If...

          1. All three strings are STRICTLY alphabetical.
          2. All three strings are STRICTLY in uppercase.
          3. If last name is equal to "LASTNAME", the firstname is equal to "FIRSTNAME". and the middle initial is "M.",
             return true, otherwise, return false.


    2. Writing Data

               
          
