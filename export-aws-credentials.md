https://github.com/benkehoe/aws-export-credentials/blob/master/README.md

when having issues with calling aws profiles I've found this can help export the credential from AWS SSO to pass it the the system.
`/Users/kmobl/Library/Python/3.11/bin/aws-export-credentials --profile <profile> -c <profile>`
