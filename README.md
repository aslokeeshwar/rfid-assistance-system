# RFID assistance system in classrooms

## Nature of Work 
Novel solution/ingenious design to a problem/challenge

## Rationale 
This system was designed keeping in mind the hassle that teachers undergo in classrooms to request for assistance regarding any matter. It focuses on eliminating this trouble and simplifying this situation to enable maximum productivity.

## Materials Used 
  
  ### FOR DEVELOPMENT
  
    i.	Arduino Uno/Arduino Nano microcontroller
    
    ii.	RC522 RFID reader
    
    iii. OLED display
    
    iv.	Push-buttons
    
    v.	10k Ω Resistors  
    
    vi.	Jumper wires
    
    vii. Breadboard/Prototype board
	
  ### FOR OPERATIONG EXHIBIT
  
    i.	USB A to USB B cable
    
    ii.	Laptop with sufficient USB ports
    
    iii. Painted enclosure/box with slots for display and power connection
    

## PROCEDURE/DESCRIPTION
  
  ### I. HARDWARE PREPARATION
  
      a. Procure all said materials and connect each to the microcontroller using jumper wires and the prototype board. 

  ### II. SOFTWARE PREPARATION
  
      a. Connect the microcontroller to a laptop with the Arduino IDE installed and open using the USB A to USB B cable. 
      
      b. Upload a test code to check if all components are working properly in order to move on to program the system.
      
      c. Once checks are done, upload the main code to the system and wait for the serial monitor readings to ensure everything is in order. (Visual cues will be  given on the OLED display also, through a small power-on message)
      
      d. Code for the same has been linked to in the References section.

  ### III. LOGIC USED
  
      a. When the RFID card is read, there is a unique code attached to each card that identifies it, called a UID. This UID is predefined for each card in the registered ecosystem. When a card that has a foreign UID is read, the system won’t work, thus preventing misuse of this system.
      
      b.  Each UID is linked to a card, and each card is linked to a faculty member in the institution, hence each UID is used to identify which user has requested for assistance and each reader system has its unique code, so each system is used to pinpoint the location of the user’s general location.
      
      c. As teachers require assistance in various fields and not just one, a database of possible issues has been added to the main microcontroller, hence the request can be more precisely filtered and catered to accordingly.
      

  ### IV. DATA ANALYSIS
  
      a. On an average, the time taken for requesting assistance in my school without the system is about 10 minutes i.e., through means of phone calls and messaging.
      
      b. Using this system, that time can drastically go down to as low as 3 minutes, depending on the availability of the requested assistance faculty.
      
      c. This system also eliminates the need for usage of mobile phones in a classroom, hence improving the classroom environment in favour of better education quality.
      

## REFERENCES 

	i. https://youtu.be/So83sH6-jwM

	ii. https://randomnerdtutorials.com/security-access-using-mfrc522-rfid-reader-with-arduino/

	iii. Stackoverflow

	iv. Arduino Community 
