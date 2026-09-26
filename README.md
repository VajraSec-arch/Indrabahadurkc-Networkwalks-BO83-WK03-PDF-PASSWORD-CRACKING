# 🔐 PASSWORD CRACKING USING JOHN THE RIPPER

## Cybersecurity Project Report


| submitted by:      | Indra bahadur kc                                                     |
| -------------- | ----------------------- |
| Project: | Week3 PDF Password cracking. |
| Instructor: | Waqas Karim (CCIE) |.


# 1. Introduction

As part of my cybersecurity studies, I completed a practical project on Password Cracking using John the Ripper and other password security tools.

The main purpose of this project was to understand how password-protected PDF files can be tested for password recovery and how password hashes are used in security systems.

During the project, I worked with OnlineHashCrack PDF Hash Extractor, Johnny GUI, John the Ripper, and NetworkWalks tools. This practical experience helped me understand password hash extraction, hash analysis, and password recovery techniques.

# 2. Project Objectives 🎯

The main objectives of my project were to understand the password cracking process, learn how password hashes are extracted from PDF files, and gain practical experience using password security tools.

I also wanted to understand the importance of strong passwords and develop responsible cybersecurity testing skills.

# 3. Tools and Technologies Used 🛠️

| Tool                                  | Description                                                     |
| ------------------------------------- | --------------------------------------------------------------- |
| OnlineHashCrack PDF Hash Extractor    | Extracted password hash information from my test PDF.           |
| John the Ripper                       | Used for password recovery attempts against the extracted hash. |
| Johnny GUI                            | Provided a graphical interface for John the Ripper.             |
| NetworkWalks Password Hash Calculator | Helped me explore password hash generation and formats.         |
| NetworkWalks Password Cracker         | Used for additional password and hash testing.                  |
| GitHub                                | Used to document and organize my project.                       |

# 4. Project Implementation ⚙️

## 4.1 PDF Hash Extraction

I began by opening the OnlineHashCrack PDF Hash Extractor website. I selected my password-protected PDF file and used the extraction feature to obtain the hash information.

The extracted output included a PDF password hash format that could be used with compatible tools such as John the Ripper.

This step helped me understand how password-related information can be extracted from a protected document for authorized security testing.

<img width="2848" height="1600" alt="Screenshot 2026-09-26 092230" src="https://github.com/user-attachments/assets/e8434dc9-8ea4-466a-b118-a15903ebedf3" />

## 4.2 Loading the Hash into Johnny GUI

After extracting the hash, I opened Johnny, the graphical user interface for John the Ripper.

I loaded the extracted hash into the application. The screenshot shows the PDF entry and its associated hash information displayed in Johnny.

This step helped me understand how hash data is imported and prepared for password recovery attempts.
<img width="2858" height="1800" alt="Screenshot 2026-09-26 102340" src="https://github.com/user-attachments/assets/ee7da824-49da-4fc1-bbfe-2166f725b872" />


## 4.3 Password Recovery Using John the Ripper

Next, I used John the Ripper to perform password recovery testing against the extracted PDF hash.

John the Ripper works by testing password candidates and checking whether they match the supplied hash. Its performance depends on the password's complexity, the selected testing method, and the available computing resources.

I used the Johnny interface to manage the activity and observe the results.

This practical step helped me understand the basic working process of password recovery tools.

<img width="2880" height="1504" alt="Screenshot 2026-09-26 090328" src="https://github.com/user-attachments/assets/974fae63-c9df-4efc-b75a-349e9a674f63" />


## 4.4 Password Hash Calculation Using NetworkWalks

I used the NetworkWalks Password Hash Calculator to explore how a password can be converted into a hash value.

This helped me understand that hash algorithms transform input data into a fixed-format output. I also learned that different algorithms produce different hash formats and that secure password storage requires suitable password-hashing methods.

<img width="2836" height="1754" alt="Screenshot 2026-09-26 103820" src="https://github.com/user-attachments/assets/baced1c3-11cd-4bb4-bb17-5fe6afea4b3d" />


## 4.5 Password Cracker 

I also explored the NetworkWalks Password Cracker to understand how password testing tools process passwords or hashes.

By using this tool alongside John the Ripper, I gained a broader understanding of password testing and the role of password complexity in security.

<img width="2848" height="1642" alt="Screenshot 2026-09-26 092130" src="https://github.com/user-attachments/assets/40f46c46-9f44-4bae-b905-4dcff876ddbf" />


# 5. Results and Observations 📊

From my practical work, I observed the process of extracting a PDF password hash and loading it into Johnny GUI for password recovery testing.

The project helped me understand that password recovery depends on the password's strength, the hash format, and the methods used by the recovery tool.


# 6. Challenges Faced and Solutions 💡

During the project, I learned how to work with different tools and understand their output.

| Challenge                     | Solution / Learning                                                                      |
| ----------------------------- | ---------------------------------------------------------------------------------------- |
| Extracting the PDF hash       | Used the PDF Hash Extractor and reviewed its output.                                     |
| Loading the hash into Johnny  | Checked the extracted hash format and imported it into the application.                  |
| Understanding hash output     | Used the hash calculator to learn about hash formats and values.                         |
| Interpreting recovery results | Reviewed the tool output and learned about password complexity and recovery limitations. |

These activities helped improve my technical understanding and troubleshooting skills.

# 7. Learning Outcomes 📚

This project helped me gain practical knowledge of password hash extraction and recovery tools.

I learned how John the Ripper works with password hashes, how Johnny GUI can simplify the process, and how password hashing relates to document security.

I also improved my ability to document technical activities, organize screenshots, and present my work professionally through GitHub.

# 8. Ethical Considerations and Security Recommendations 🛡️

I carried out this project for educational purposes and focused on authorized password recovery testing.

The project reinforced the importance of using long and unique passwords, protecting sensitive files, and avoiding password reuse.

I also learned that password hashes and recovered credentials must be handled securely and that password testing should only be conducted with appropriate authorization.

# 9. Conclusion

In conclusion, my Password Cracking project was a valuable part of my cybersecurity learning journey.

By using OnlineHashCrack, Johnny GUI, John the Ripper, and NetworkWalks tools, I gained a better understanding of password hash extraction, password recovery, and the importance of secure authentication.

The project improved my technical knowledge, practical experience, and documentation skills. It also encouraged me to continue learning about ethical hacking and information security.

# 10. References

1. John the Ripper: https://www.openwall.com/john/
2. OnlineHashCrack: https://www.onlinehashcrack.com/
3. NetworkWalks: https://www.networkwalks.com/
4. Course materials and instructions provided by my instructor Mr Waqas Karim (CCIE).
