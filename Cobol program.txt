       IDENTIFICATION DIVISION.  
       PROGRAM-ID.  ADD-NUMBERS.  
       DATA DIVISION.  
       WORKING-STORAGE SECTION.  
       01  A           PIC 9(3) VALUE 1.  
       01  B           PIC 9(3) VALUE 1.  
       01  RESULT      PIC 9(3).  
       PROCEDURE DIVISION.  
           ADD A TO B GIVING RESULT.  
           DISPLAY "A = " A.  
           DISPLAY "B = " B.  
           DISPLAY "A + B = " RESULT.  
           STOP RUN.