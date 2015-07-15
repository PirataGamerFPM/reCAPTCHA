## esoTalk – reCAPTCHA plugin

- Protect your forum from spam and abuse while letting real people pass through with ease.

### Release Note

- esoTalk version 1.0.0g4 and beyond is required!

### Installation

Browse to your esoTalk plugin directory:
```
cd WEB_ROOT_DIR/addons/plugins/
```

Clone the reCAPTCHA plugin repo into the plugin directory:
```
git clone git@github.com:tvb/reCAPTCHA.git reCAPTCHA
```

Chown the reCAPTCHA plugin folder to the right web user:
```
chown -R apache:apache reCAPTCHA/
```

### Translation

Create `definitions.reCAPTCHA.php` in your language pack with the following definitions:

```
$definitions["Are you human?"] = "Você é um humano?";
$definitions["Secret Key"] = "Código secreto";
$definitions["Site Key"] = "Código do site";
$definitions["Language"] = "Idioma";
$definitions["message.reCAPTCHA.settings"] = "Insira seus códigos reCAPTCHA (<a href='https://www.google.com/recaptcha/admin#whyrecaptcha' target='_blank'>Não tem nenhum código? Crie um aqui</a>)";
$definitions["message.invalidCAPTCHA"] = "O CAPTCHA é inválido. Tente novamente";
```

### Screenshots
Sign Up page
![Sign Up page](http://i.imgur.com/jBgbQ6C.png)

reCAPTCHA in action
![Wrong CAPTCHA](http://i.imgur.com/uKHp8rY.png)

reCAPTCHA Settings
![reCAPTCHA Settings](http://i.imgur.com/lzqy6ue.png)
