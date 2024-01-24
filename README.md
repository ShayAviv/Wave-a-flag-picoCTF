picoCTF Wave a flag

![image](https://github.com/SiniKatan/Wave-a-flag-picoCTF/assets/153393575/b2e7ef66-8b54-4a09-9a22-595d2332df86)

let's download the link of the file using the 'wget' command

![צילום מסך 2024-01-24 080916](https://github.com/SiniKatan/Wave-a-flag-picoCTF/assets/153393575/0f9eda5c-ac05-4bb9-bcbe-80f7f25fa045)

now we need to change the file permissions - The task involves providing a link for downloading a 64-bit ELF Executable file titled "warm". Attempting to execute it using: ./warm,but it wouldn't work because you don't have permissions - so we will use the 'chmod' command and give the file the execute premission.


![צילום מסך 2024-01-24 081015](https://github.com/SiniKatan/Wave-a-flag-picoCTF/assets/153393575/7abeae91-f5f3-4da7-ab7a-8dd8453389da)



now let's use the './warm' command

![צילום מסך 2024-01-24 081021](https://github.com/SiniKatan/Wave-a-flag-picoCTF/assets/153393575/98f5612e-62c6-4ac5-af24-38e08f4f8158)

they told us to use './warm -h' command

![צילום מסך 2024-01-24 081044](https://github.com/SiniKatan/Wave-a-flag-picoCTF/assets/153393575/ff14ffff-1303-46b9-a38a-d1bf4d77d64a)

and that's the flag - picoCTF{b1scu1ts_4nd_gr4vy_6635aa47}


