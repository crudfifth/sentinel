# Sentinel

**Sentinel** is a secure, CLI-based password manager built with Ada and SPARK Ada. The goal is to provide a reliable, high-security tool for managing passwords and sensitive data, ensuring data integrity and protection at all stages.

## Features

- **Password Generation**: Generate strong, random passwords.
- **Password Storage**: Securely store passwords with encryption.
- **Password Retrieval**: Retrieve passwords with decryption.
- **File Storage**: Save encrypted password data to a local file.
- **Security**: Built with Ada and SPARK Ada, leveraging formal methods for safety and reliability.

## Requirements

- Ada compiler (GNAT)
- SPARK Ada (for formal verification)
- External libraries for encryption (e.g., AES)

## Setup

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/Sentinel.git
   cd Sentinel
   ```

2. **Install GNAT (Ada compiler)**:

   For Ubuntu:

   ```bash
   sudo apt-get install gnat
   ```

   For macOS (using Homebrew):

   ```bash
   brew install gnat
   ```

3. **Install Alire (Ada package manager)**:

   ```bash
   curl -sSL https://github.com/alire-project/alire/releases/download/v1.0.0/alire-linux-x86_64 -o /usr/local/bin/alire
   chmod +x /usr/local/bin/alire
   ```

4. **Install dependencies** (if any external libraries are needed, such as encryption libraries):

   ```bash
   alire fetch <package-name>
   ```

5. **Build the project**:

   ```bash
   alire build
   ```

6. **Run Sentinel**:

   ```bash
   ./sentinel
   ```

## Usage

To start using Sentinel, simply run the application and follow the prompts. The CLI allows you to securely manage your passwords by adding, retrieving, and deleting entries. Each action is performed with high-level encryption to ensure your data is kept safe.

## Contributing

If you’d like to contribute to Sentinel, feel free to open an issue or submit a pull request. All contributions are welcome, whether it’s adding features, fixing bugs, or improving documentation.

## License

Sentinel is licensed under the MIT License. See LICENSE for more information.

