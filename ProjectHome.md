Create an exact path-to-path dynamic mirror (proxy) for a pre-defined site.

## Restrictions ##

  * NOT work for absolute URL (with full site domain). Since this is an exact mirror, content of HTTP response will be transfered without any modification. That means, if the original site uses absolute URL instead relative path, the page may not be rendered correctly, or visitor will be redirected to the original site.

  * NOT work for web page with `<BASE>` HTML tag. The reason is the same as above.

## Instructions ##

Unzip the package to your PHP hosting, either in domain root or under sub-path (for patial mirror).
Modify the index.php (see comments)

## Example working target sites ##

  * yourapp.appspot.com (Only if the app is following the above restrictions)
  * bit.ly & j.mp
  * twitter.com


## **IMPORTANT WARNING** ##

Full mirroring any restricted sites may bring **PERMANENT DISASTER** to your site, to your subnet, to your hosting service, or event to **all the sites on the same hosting**. So, please use it as your private service and **DO NOT DISTRIBUTE YOUR MIRROR**.