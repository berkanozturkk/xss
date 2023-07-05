# xss
Two examples of scripts that i wrote, vulnerable to XSS and safe to XSS

Cross-site Scripting (XSS) is a client-side code injection attack that attacker can fetch sensitive data, cookie theft, malicious downloads, media content etc. Main idea behind the XSS is attackers firslty injects malicious scripts into vulnerable web page or application (most of the time via JavaScript). 

To keep ourself safe from XSS, we should sanitize and filter all of our variables, we should always validate our inputs if it is expected or not.. Where user-provided data is output in responses, outputs should not be interpreted as active code instead of text (output encoding). 
