# Dirbuster Docker image
A Docker image of [Dirbuster](https://www.owasp.org/index.php/Category:OWASP_DirBuster_Project), to brute force directories and files names on web/application servers.

## Usage:

    docker run --rm hypnza/dirbuster -u <url>

## Example:

    ~: docker run --rm hypnza/dirbuster -u http://example.com
    Dec 05, 2017 7:37:14 AM java.util.prefs.FileSystemPreferences$1 run
    INFO: Created user preferences directory.
    Starting OWASP DirBuster 0.12 in headless mode
    Starting dir/file list based brute forcing
    Dir found: / - 200

## Wordlists:

    /DirBuster-0.12/apache-user-enum-1.0.txt
    /DirBuster-0.12/apache-user-enum-2.0.txt
    /DirBuster-0.12/directory-list-1.0.txt
    /DirBuster-0.12/directory-list-2.3-big.txt
    /DirBuster-0.12/directory-list-2.3-medium.txt
    /DirBuster-0.12/directory-list-2.3-small.txt
    /DirBuster-0.12/directory-list-lowercase-2.3-big.txt
    /DirBuster-0.12/directory-list-lowercase-2.3-medium.txt
    /DirBuster-0.12/directory-list-lowercase-2.3-small.txt
