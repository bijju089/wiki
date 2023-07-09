---
sidebar_position: 1
---

# Change Navbar Logo 
This page will tell you how to change Navbar, Portal logo image.

1. Login to your ACP and go to Layout > Images
2. Upload new logo image
3. Click on submit button

## Change Logo Size
1. Logon to your FTP client (ex, FileZilla)
2. Go to folder > custom > templates > Aurora
3. Open the file navbar.tpl
4. At line 27 Modify `max-width` and set it according to you
  ```smarty
{if isset($LOGO_IMAGE)} <img class="ui small image" style="max-width:80px;"src="{$LOGO_IMAGE}"> {else} <h2>{$SITE_NAME} </h2> {/if}```

### Community Support
Feel free to join our [discord](https://discord.gg/creativmap) server for template support.