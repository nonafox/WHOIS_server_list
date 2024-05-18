# About
This is a project to help you fetch the newest WHOIS-server list.
- `list.dat` is the list in the format of `.ext whois.server.host`. Update it by using `go.php`.
- `list.php` is the auto-require version of the list in PHP. It will pull in an global array-like variable called `$whois_servers`. Update it by using `trans.php`.
- `go.php` will take you to update the list. If the previous operation is aborted, it will continue to begin at the last position.
- `trans.php` will translate the `list.dat` file into its PHP version `list.php`.
