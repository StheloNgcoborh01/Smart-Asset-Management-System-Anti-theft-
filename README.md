# Smart Access Management System (SAM)
-Originally developed in 2024 as a university/hardware project

#overview
-A hybrid software + hardware system for tracking and managing assets.  
-Staff and students can borrow assets, and the system verifies access before allowing borrowing.

#Software
-C# Windows Forms application
-Connects to SQL database to verify users
-Interacts with hardware via serial port

#Hardware
-Microcontroller handles logic
-Barcode scanner to scan assets
-LCD displays "Access Granted"/"Denied"
-etc..

#key feautures
- VerifyStaff: checks staff credentials, sends signals to hardware
- FormAssetCatalog: manages asset borrowing/return UI
- CaesarEncryption: simple encryption for secure data
- Database queries: tracks staff and borrowed assets


⚠️ This is a hybrid software + hardware project.  
Some parts (serial communication, LCD, barcode scanner) may not run on a standard PC.  
Code is provided for portfolio demonstration purposes.

#My contributions
- Implemented staff verification logic and serial port communication
- Developed Windows Forms UI for asset catalog
- Implemented encryption methods




