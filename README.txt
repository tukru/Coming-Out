# Hidden Files Bash Bunny Payload

This is a Bash Bunny payload that uses a PowerShell script to search for hidden image files in the user's profile directory. The script ignores files with image extensions and checks the file headers for known image file headers. The output is saved to a CSV file in the loot directory.


## Requirements

To use this payload, you will need:

- A Bash Bunny
- A computer running Windows or Linux

## Usage

1. Copy the payload code to a text file with the extension ".txt" (e.g., "hidden-files-payload.txt").

2. Copy the payload file to the "payloads" directory on the Bash Bunny's flash drive.

3. Switch the Bash Bunny to arming mode.

4. Use the switch position that corresponds to the filename of the payload to run the payload (e.g., if you saved the payload as "hidden-files-payload.txt", use switch position 1 to run the payload).

5. The output will be saved to a CSV file in the "/root/loot/image-files" directory on the Bash Bunny's flash drive.

## Credits

This project was inspired by the "Hidden_Images" project by Paul Murton on the Hak5 Git repository.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
