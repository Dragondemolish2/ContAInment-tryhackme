So we know from the start that we have SSH access so we SSH into the target.

<img width="892" height="692" alt="Screenshot 2026-05-13 114548" src="https://github.com/user-attachments/assets/fdf0ddc5-6fd8-4e9d-ae01-adefb59e513f" />

<img width="865" height="639" alt="Screenshot 2026-05-13 115501" src="https://github.com/user-attachments/assets/38f01c2f-cd43-4621-9f5b-6118a7838ef8" />

Now we search for all the session pcap dump and we check the sizes of all the files to find abnormal sizes.

<img width="845" height="630" alt="Screenshot 2026-05-13 115857" src="https://github.com/user-attachments/assets/2a353fb4-14ff-4a0c-8bdc-65b8e1e44add" />

We then go to our AI assistant to help us reassemble the file so we can read the file.

<img width="686" height="185" alt="Screenshot 2026-05-13 123720" src="https://github.com/user-attachments/assets/31d6dd31-8a7c-42e1-8466-8085982f93a1" />

Make sure that you have downloaded the pcap file and you enter the correct directory for the AI to scan it and rebuild it.

<img width="665" height="90" alt="Screenshot 2026-05-13 130012" src="https://github.com/user-attachments/assets/56453d71-f0df-44fc-b071-559c67fd8cb4" />
<img width="990" height="583" alt="Screenshot 2026-05-13 125958" src="https://github.com/user-attachments/assets/486a0225-ae04-4b1d-94d5-30c0e2c073dd" />

Now that we have the rebuilt file we search through the file to find the target email and password to access the zip file and extract its data.

<img width="835" height="247" alt="Screenshot 2026-05-13 130407" src="https://github.com/user-attachments/assets/2dcaedb2-9815-4963-a0e1-b475ecde19e2" />

<img width="919" height="29" alt="Screenshot 2026-05-13 130617" src="https://github.com/user-attachments/assets/a1e2da35-c30b-4b9a-b311-c316879f8ab3" />

Inspect the file and access the the flags file to find some encryptions. We then return to the AI to use the liberty prime tool to decrypt this into our flag.

<img width="720" height="245" alt="Screenshot 2026-05-13 130809" src="https://github.com/user-attachments/assets/09b3fa8b-2dff-47ee-a0e7-eefb26e46782" />
