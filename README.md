# Hello-World
My first little project
Hi I'm David. I come from Colombia and I want to learn about coding and software. I've been working as a technician operator in Vente-privee, and my work is interesting because I learn everyday. This time I write a list with possible configurations to solve an alert:

# Alerts:
- PROCS WARNING {Icinga > Activity_log > CLICK NAME >Services-Inherited from Linux > Check_total_process_nrpe > NRPE Command- [check_process]                                                                                                                    [check_process_hot]                                                                                                                            [check_process_hot_and_spicy] }

- CHECK_NRPE {Remote desktop connection > Adm. Tools > services > compare_nsclient.ini  > Notepad - Run as administrator > copy_nsclient.ini > Save as nsclient.ini > restart}

SNMP :

State critical or Unknown: Check uptime (snmp)- Connect snmp remotely :

     Fixing steps:
         https://www.gfi.com/support/products/gfi-archiver/How-to-manually-force-a-service-to-stop-if-not-responding
    1- Click the Start menu
    2- Click Run or in the search bar type services.msc
    3- Press Enter
    4- Look for the service and check the Properties and identify its service name
    5- Once found, open a command prompt. Type sc queryex [servicename].
    6- Press Enter
    7- Identify the PID
    8- In the same command prompt type taskkill /pid [pid number] /f
    9- Press Enter

                                                                                                                                                  
