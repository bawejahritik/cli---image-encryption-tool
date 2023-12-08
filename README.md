# cli---image-encryption-tool

This is a command-line tool written in Go for encrypting images. It uses the AES-256 cipher to encrypt the image with a password provided by the user.

**Usage:**

To encrypt an image, run the following command:

```
go run . encrypt <image_file_path>
```

You will be prompted to enter a password and a prompt to confirm the password. The encrypted image will be saved in the same directory as the original image.
To decrypt an image, run the following command:

```
go run . decrypt <encrypted_image_file_path>
```

You will be prompted to enter the password used to encrypt the image. The decrypted image will be saved in the same directory as the encrypted image.

**Commands:**

* `encrypt`: Encrypts an image given a password.
* `decrypt`: Tries to decrypt a file using a password.
* `help`: Displays help text.

**Example:**

To encrypt an image called `my_image.jpg` with the password `secret`, run the following command:

```
go run . encrypt my_image.jpg
```

This will create an encrypted image called `my_image.jpg`.

To decrypt the encrypted image, run the following command:

```
go run decrypt my_image.jpg
```

This will create a decrypted image called `my_image.jpg`.


**Notes:**

* This tool is still under development, and there may be bugs.
* It is important to keep your password safe. If you lose your password, you will not be able to decrypt your encrypted images.

**Contributions:**

All contributions are welcome! Please feel free to open an issue or submit a pull request.
