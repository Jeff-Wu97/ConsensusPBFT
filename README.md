# Distributed-Fintech-Infrastructure-Testbed

## Final Update: Dissertation Submitted
This is the last update for mobile fintech infrastructure app. The dictionary *Zyzzyva* is uploaded to test the transaction based on Zyzzyva. The dictionary *TestPBFT* and *TestZyzzyva* are two project files for performance measurement for batch trsaction with PBFT and Zyzzyva. Please install the Android Studio before running these files.

Thank You!

## Update: Layout Optimization
The new layout in *PBFT_v3* is friendly for user operation. It could be run as a good Android Studio demo of a transaction on 4-nodes mobile network. Do not forget to run the *tel_redir.py* first! 

If you would like to catch main codes, which has been modified easy to go through, please visit this page https://github.com/Jeff-Wu97/Distributed-Fintech-Infrastructure-Testbed/tree/master/PBFT_v3/app/src/main/java/com/example/commdemo.


Thanks.

## Update: View-Change Protocol
The View-Change protocol has been implemented in the dir *PBFT_v2*, which is an Andriod demo. This demo is integrated with the Schnorr signature and verification mechanism. 


To interconnecting emulator instances, a script code *tel_redir.py* has been uploaded to redirect ports, so that you needn't start telnet session manually anymore.


Thank you!

## Update: ECSchnorr Signature
The *Schnorr.java* contains a demo for ECSchnorr signature. It creates EC keypairs, generates Schnorr signature, and verify the message with signature. The encrypted string is "HelloWorld" (defined at row 273, main). Welcome to run the demo on your Eclipse!

## Mobile PBFT 
Thanks for your visit!

With the advancement of Internet financial technology, the transaction security is drawing more public attention. The consensus algorithms is applied in distributed financial systems to ensure transaction consistency. This ongoing project aims to explore implementation consensus algorithms based on mobile.

The *PBFTDemo* is an Android project of the practical Byzantine fault tolerance algorithm. To run the demo, you'd better to install the Android Studio first. Then import the "PBFTDemo" project directly. If you would like to run the demo on the emulator, you need to create the virtual machine in Android Studio by "Tools" - "AVD Manager". Then, you should redirect the ports. Modify the "port_arr" and "port_send_arr" in "SystemInfo" class of *MainActivity.java* file (*PBFTDemo/app/src/main/java/com/example/commdemo/MainActivity.java*), which contain the listening port and the port redircting to the listening port. After that, please set port redir according to the page https://developer.android.com/studio/run/emulator-networking?hl=zh-cn. (A script code to simplify the step is on the way.)

If you have any questions, welcome to contact me <Z.Wu-28@sms.ed.ac.uk>.
