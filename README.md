# KDR-Custom-Form-Shortcode
A wordpress plugin provide you custom form tag html using shortcode in a nice ways!

## How to Use
1. Download or clone this code
2. Unzip and place in wp-content/plugins/ directory
3. Activate the plugins!

## The Shortcodes 
**1. Form Open** <br>
Use `[kdr_form_open]` to generate form open tag html, it will generates:

```html
<form action="" method="get" class="form-inline">
```
<i>Options:</i> <br>
**action**: The action url for the form <br>
**method**: GET/POST (default: GET) <br>
**class**: class for the form (default: form-inline) <br><br>
<i>More Example:</i> <br>
`[kdr_form_open action="/login" method="POST" class="form-stacked"]` will generates:
```html
<form action="/login" method="POST" class="form-stacked">
```

**2. Form Close** <br>
Use `[kdr_form_close]` to generate form open tag html, it will generates:

```html
</form>
```

**3. Form Label** <br>
Use `[kdr_label]` to generate labels

Examples:
`[kdr_label label="Your Name"]`, it will generates:
```html 
<label>Your Name</label>
```

**4. Input** <br>
Use `[kdr_input]` to generates form input

Examples: `[kdr_input type="text" label="Your Name" class="form-control input-lg"]`, it will generates:
```html
<div class="form-group">
   <label>Your Name</label>
   <input type="text" name="your_name" class="form-control input-lg" value="">
</div>
```

## More Information
Working only using Bootstrap v3.x

If you have any questions, say hello to halo@kodrindonesia.com

*Made with bunch of coffee at Bandung by Kodr Indonesia*