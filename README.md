# UDP-File-Transfer

### Description:
I've developed a file transfer application using C++ on Windows, utilizing UDP for communication. This application allows users to reliably send both ASCII and binary files over the network. It incorporates a brief protocol for transmitting file information and contents while ensuring the integrity of the transferred files through whole-file error detection mechanisms.

### Tools Used:
I utilized C++ for the development, leveraging the Windows platform for compatibility. To ensure reliable communication over the network, I implemented UDP. For version control and project management, I used Git.

### Features:
- Reliable transmission of both ASCII and binary files over UDP.
- Brief protocol for transmitting file information and contents.
- Whole-file error detection mechanism to ensure data integrity.
- Dynamic calculation and display of transmission time and transfer speed in megabits per second.
- Integration of tests for normal functionality and error cases.
- Compatibility with physically separate machines for testing purposes.

### Install and Run Instructions:
1. Clone the repository from GitHub.
2. Navigate to the project directory.
3. Compile the source code using a C++ compiler compatible with Windows.
4. Run the executable file generated after compilation.
5. Follow the on-screen instructions to specify the file to be transferred and initiate the transmission.

### Interesting Parts during the Build Process:
One interesting aspect was devising the protocol for transmitting file information and contents efficiently over UDP while ensuring reliability. Implementing the whole-file error detection mechanism was also intriguing, as it required careful consideration of various algorithms and their integration into the application.

### Difficulties we had and how we overcame them:
One challenge was accurately measuring the transmission time and calculating transfer speed, especially considering fractional seconds. I overcame this difficulty by researching and implementing precise timing mechanisms within the application, ensuring accurate measurement of transmission time and subsequent calculation of transfer speed.

### Future Updates and Fixes:
In future updates, I plan to enhance the user interface to provide a more intuitive experience. Additionally, I aim to optimize the application for even faster file transfers and potentially explore incorporating more advanced error detection and correction techniques. Bug fixes and performance improvements will also be priorities based on user feedback and testing results.

<img width="819" alt="Screenshot 2024-05-07 at 6 44 13 PM" src="https://github.com/shubhhh19/UDP-File-Transfer/assets/126296317/f775d886-aa8a-4c79-a5bb-15f010de320d">
