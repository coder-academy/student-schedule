#### Week 5 Tuesday Day 2

---

## Tuesday's Subject
Term 1 Project #1

---

## Tuesday's Challenge
Term 1 Project #1

### Add a favicon to your website.

Add this to your `<head>`, and put your `favicon.ico` file at the top of your site (next to your index.html).
```
<link rel="icon" href="/favicon.ico" type="image/x-icon">
```

Browsers will automatically look for a favicon at `www.example.com/favicon.ico`, so that’s why it must be placed there.

Generate a favicon: 
http://www.favicomatic.com/

### Test with a micro web server

```
cd YOUR_WEBSITE_FOLDER
php -S localhost:9000
```

(On Windows, instead of PHP you could try out mongoose: http://stackoverflow.com/a/5119307 or tinyweb: http://ccm.net/faq/2568-tinyweb-server-on-windows)

Visit `http://localhost:9000/` is your web browser

This is a mini webserver, which lets you test it like on a real website.

This allows you to use absolute paths for your favicon and CSS. e.g. `/favicon.ico` not `favicon.ico`, and always `/styles/main.css` not `styles/main.css` or `../styles/main.css` for a nested HTMl file.
