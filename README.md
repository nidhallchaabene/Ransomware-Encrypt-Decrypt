<h1>Ransomware (Encrypter and Decrypter)</h1>



<h2>Description</h2>
EncryptorDecryptorPOC is a pair of simple command-line utilities written in C# for encrypting and decrypting files with a specific password and file extension. These projects demonstrate basic file encryption and decryption using the AES encryption algorithm.

<br />
<br />
-<b>Encrypter</b>
<br /><br />
EncryptorPOC is designed to encrypt files with a specific password and file extension. It offers the following features:<br /><br />

- Encrypt files in specified folders: Desktop, Pictures, and Documents.
- Append a custom file extension to encrypted files.
  
-<b>Decrypter</b><br /><br />
DecrypterPOC is designed to decrypt files that have been encrypted using a specific password and file extension. It offers the following features:

- Decrypt files in specified folders: Desktop, Pictures, and Documents.
- Remove encrypted files after successful decryption.
- Generate a decryption log for reference.

<h2>Languages and Utilities Used</h2>

- <b>C#</b> 






<h2>Program Walkthrough:</h2>

<p align="center">
Directories Before Encryption: <br/>
<img src="https://imgur.com/E6Kio9P.png" height="80%" width="80%" alt="encryption before"/>
<br />
<br />
Directories After Encryption: <br/>
<img src="https://imgur.com/wOLZDOF.png" height="80%" width="80%" alt="encryption after"/>
<img src="https://imgur.com/yt2dY14.png" height="80%" width="80%" alt="encryption after"/>
<img src="https://imgur.com/WH359gf.png" height="80%" width="80%" alt="encryption after"/>
<br />
<br />
Directories After Decryption: <br/>
<img src="https://imgur.com/JrlaWDd.png" height="80%" width="80%" alt="decryption"/>
<br />
<br />
