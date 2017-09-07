# Host Switch Plus - Chrome Extension
Version：1.3.11

This product has been altered from the original version from a purely vain western presumption that Americans do not want to see other languages in their markup. The principle behind the plugin is solid, and therefore some styling, JS and other alterations were desired. The plugin itself allows you to simply add routes to your browser session to rewrite the request to another location. The effect is similar to altering the hosts file; the effects only extend to the browser while the plugin is enabled and the host record is enabled, allowing the ability to quickly a/b test a domain with the plugin.

The session is notated with a small indicator div in the bottom left hand corner of the site when rewriting has occurred and the console is logged with the redirection date and time.

The input format for bulk importing of host records is equally simple and follows a simple format [IP, domain, tag(optional - comma delimited), notes(optional)]. Each value is space delimited, the first 2 fields are required and the last 2 fields are optional.

A simple list would look like：
```
127.0.0.1:8888 www.xyz.com prod Fiddler
127.0.0.1 *.xyz.com multiple,tags,look,like,this And then your notes fill up the rest.
192.168.1.2 www.xyz.com
```
