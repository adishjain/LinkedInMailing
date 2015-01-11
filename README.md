LinkedInMailing
===============
Sends email to any Recruiter/Talent Acquisitionist with a copy of your resume and a small message from your LinkedIn network.
It takes in your contact list from LinkedIn in .csv format, reusme copy, and the message in a text file.

- Get your contact list from here: https://www.linkedin.com/people/export-settings
- The message should replace the Recruiter's name tag with {Name} and Company's name tag with {Company}

```
    usage: mail.py [-h] [-ex old_file] sender_list attach_path text_body
      
    Sends email with attachment to multiple recipients.
      
    positional arguments:
        sender_list         Path to the text file containing list of senders
        attach_path         Path to the attachment file
        text_body           Path to the text file containing email message
        
    optional arguments:
        -h, --help          show this help message and exit
        -ex old_file, --exclude old_file
                            Compare new contact file with old and send the mail to
                            new ones only
```
