# Code Citations

## License: unknown
https://github.com/hangnguyen306/vitadary/blob/013a0bb1da3d10635120dc67463a4602a735c089/src/sass/pages/_tuvandinhduong.scss

```
````html
<!-- filepath: c:\Users\User\Desktop\invitation\wedding.html -->
<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Ұл тойға шақыру - Имран, Ақмаль мен Әлинұрдың құрметіне арналған ұл тойы">
    <meta name="theme-color" content="#1a1a1a">
    
    <!-- Open Graph Tags -->
    <meta property="og:title" content="Ұл тойға шақыру">
    <meta property="og:description" content="Сіздерді ұлдарымыздың құрметіне арналған ұл тойымыздың қадірлі қонағы болуға шақырамыз!">
    <meta property="og:type" content="event">
    <meta property="og:image" content="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 1200 630'%3E%3Crect fill='%23d4af37' width='1200' height='630'/%3E%3Ctext x='600' y='315' font-size='48' text-anchor='middle' fill='%231a1a1a' font-family='serif'%3EҰл тойға шақыру%3C/text%3E%3C/svg%3E">
    
    <title>Ұл тойға шақыру | Tusau Kesew Celebration</title>
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --primary-gold: #d4af37;
            --dark-bg: #1a1a1a;
            --light-bg: #f9f7f4;
            --text-dark: #2d2d2d;
            --text-light: #f9f7f4;
            --accent-brown: #8b6f47;
            --accent-cream: #ede4d3;
        }

        @media (prefers-color-scheme: dark) {
            :root {
                --bg-primary: #1a1a1a;
                --bg-secondary: #2d2d2d;
                --text-primary: #f9f7f4;
                --text-secondary: #d4af37;
            }
        }

        @media (prefers-color-scheme: light) {
            :root {
                --bg-primary: #f9f7f4;
                --bg-secondary: #ede4d3;
                --text-primary: #2d2d2d;
                --text-secondary: #8b6f47;
            }
        }

        body {
            font-family: 'Georgia', 'Noto Serif', serif;
            background-color: var(--dark-bg);
            color: var(--text-light);
            line-height: 1.6;
            overflow-x: hidden;
        }

        @media (prefers-color-scheme: light) {
            body {
                background-color: var(--light-bg);
                color: var(--text-dark);
            }
        }

        /* Pattern Background */
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-image: 
                repeating-linear-gradient(45deg, transparent, transparent 35px, rgba(212, 175, 55, 0.03) 35px, rgba(212, 175, 55, 0.03) 70px);
            pointer-events: none;
            z-index: 0;
        }

        main {
            position: relative;
            z-index: 1;
        }

        /* Header */
        header {
            background: linear-gradient(135deg, rgba(26, 26, 26, 0.95) 0%, rgba(139, 111, 71, 0.95) 100%);
            padding: 3rem 2rem;
            text-align: center;
            border-bottom: 3px solid var(--primary-gold);
            animation: slideDown 0.8s ease-out;
        }

        @media (prefers-color-scheme: light) {
            header {
                background: linear-gradient(135deg, rgba(237, 228, 211, 0.98) 0%, rgba(212, 175, 55, 0.15) 100%);
                border-bottom: 3px solid var(--primary-gold);
            }
        }

        @keyframes slideDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .header-icon {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }

        h1 {
            font-size: 2.5rem;
            color: var(--primary-gold);
            margin-bottom: 0.5rem;
            font-weight: 400;
            letter-spacing: 1px;
        }

        .subtitle {
            font-size: 1rem;
            color: var(--accent-cream);
            font-style: italic;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 1.8rem;
            }
            
            .subtitle {
                font-size: 0.9rem;
            }

            header {
                padding: 2rem 1rem;
            }
        }

        /* Container */
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 3rem 2rem;
        }

        /* Greeting Section */
        .greeting {
            text-align: center;
            margin-bottom: 3rem;
            animation: fadeInUp 1s ease-out 0.2s both;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .greeting h2 {
            font-size: 1.8rem;
            color: var(--primary-gold);
            margin-bottom: 1.5rem;
            font-weight: 400;
        }

        .greeting p {
            font-size: 1.1rem;
            line-height: 1.8;
            color: var(--text-light);
            margin-bottom: 1rem;
        }

        @media (prefers-color-scheme: light) {
            .greeting p {
                color: var(--text-dark);
            }
        }

        /* Decorative Divider */
        .divider {
            width: 100px;
            height: 2px;
            background: linear-gradient(90deg, transparent, var(--primary-gold), transparent);
            margin: 2rem auto;
        }

        /* Event Details Box */
        .event-details {
            background: linear-gradient(135deg, rgba(212, 175, 55, 0.15) 0%, rgba(139, 111, 71, 0.1) 100%);
            border: 2px solid var(--primary-gold);
            border-radius: 8px;
            padding: 2.5rem;
            margin: 3rem 0;
            animation: fadeInUp 1s ease-out 0.4s both;
            position: relative;
            overflow: hidden;
        }

        .event-details::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            
```


## License: unknown
https://github.com/yemunhtetoo/m9updatedfile/blob/19f3db270ead6a272700fb0346fc62a766d47e97/css/pagetest.css

```
````html
<!-- filepath: c:\Users\User\Desktop\invitation\wedding.html -->
<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Ұл тойға шақыру - Имран, Ақмаль мен Әлинұрдың құрметіне арналған ұл тойы">
    <meta name="theme-color" content="#1a1a1a">
    
    <!-- Open Graph Tags -->
    <meta property="og:title" content="Ұл тойға шақыру">
    <meta property="og:description" content="Сіздерді ұлдарымыздың құрметіне арналған ұл тойымыздың қадірлі қонағы болуға шақырамыз!">
    <meta property="og:type" content="event">
    <meta property="og:image" content="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 1200 630'%3E%3Crect fill='%23d4af37' width='1200' height='630'/%3E%3Ctext x='600' y='315' font-size='48' text-anchor='middle' fill='%231a1a1a' font-family='serif'%3EҰл тойға шақыру%3C/text%3E%3C/svg%3E">
    
    <title>Ұл тойға шақыру | Tusau Kesew Celebration</title>
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --primary-gold: #d4af37;
            --dark-bg: #1a1a1a;
            --light-bg: #f9f7f4;
            --text-dark: #2d2d2d;
            --text-light: #f9f7f4;
            --accent-brown: #8b6f47;
            --accent-cream: #ede4d3;
        }

        @media (prefers-color-scheme: dark) {
            :root {
                --bg-primary: #1a1a1a;
                --bg-secondary: #2d2d2d;
                --text-primary: #f9f7f4;
                --text-secondary: #d4af37;
            }
        }

        @media (prefers-color-scheme: light) {
            :root {
                --bg-primary: #f9f7f4;
                --bg-secondary: #ede4d3;
                --text-primary: #2d2d2d;
                --text-secondary: #8b6f47;
            }
        }

        body {
            font-family: 'Georgia', 'Noto Serif', serif;
            background-color: var(--dark-bg);
            color: var(--text-light);
            line-height: 1.6;
            overflow-x: hidden;
        }

        @media (prefers-color-scheme: light) {
            body {
                background-color: var(--light-bg);
                color: var(--text-dark);
            }
        }

        /* Pattern Background */
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-image: 
                repeating-linear-gradient(45deg, transparent, transparent 35px, rgba(212, 175, 55, 0.03) 35px, rgba(212, 175, 55, 0.03) 70px);
            pointer-events: none;
            z-index: 0;
        }

        main {
            position: relative;
            z-index: 1;
        }

        /* Header */
        header {
            background: linear-gradient(135deg, rgba(26, 26, 26, 0.95) 0%, rgba(139, 111, 71, 0.95) 100%);
            padding: 3rem 2rem;
            text-align: center;
            border-bottom: 3px solid var(--primary-gold);
            animation: slideDown 0.8s ease-out;
        }

        @media (prefers-color-scheme: light) {
            header {
                background: linear-gradient(135deg, rgba(237, 228, 211, 0.98) 0%, rgba(212, 175, 55, 0.15) 100%);
                border-bottom: 3px solid var(--primary-gold);
            }
        }

        @keyframes slideDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .header-icon {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }

        h1 {
            font-size: 2.5rem;
            color: var(--primary-gold);
            margin-bottom: 0.5rem;
            font-weight: 400;
            letter-spacing: 1px;
        }

        .subtitle {
            font-size: 1rem;
            color: var(--accent-cream);
            font-style: italic;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 1.8rem;
            }
            
            .subtitle {
                font-size: 0.9rem;
            }

            header {
                padding: 2rem 1rem;
            }
        }

        /* Container */
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 3rem 2rem;
        }

        /* Greeting Section */
        .greeting {
            text-align: center;
            margin-bottom: 3rem;
            animation: fadeInUp 1s ease-out 0.2s both;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .greeting h2 {
            font-size: 1.8rem;
            color: var(--primary-gold);
            margin-bottom: 1.5rem;
            font-weight: 400;
        }

        .greeting p {
            font-size: 1.1rem;
            line-height: 1.8;
            color: var(--text-light);
            margin-bottom: 1rem;
        }

        @media (prefers-color-scheme: light) {
            .greeting p {
                color: var(--text-dark);
            }
        }

        /* Decorative Divider */
        .divider {
            width: 100px;
            height: 2px;
            background: linear-gradient(90deg, transparent, var(--primary-gold), transparent);
            margin: 2rem auto;
        }

        /* Event Details Box */
        .event-details {
            background: linear-gradient(135deg, rgba(212, 175, 55, 0.15) 0%, rgba(139, 111, 71, 0.1) 100%);
            border: 2px solid var(--primary-gold);
            border-radius: 8px;
            padding: 2.5rem;
            margin: 3rem 0;
            animation: fadeInUp 1s ease-out 0.4s both;
            position: relative;
            overflow: hidden;
        }

        .event-details::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            
```


## License: unknown
https://github.com/hangnguyen306/vitadary/blob/013a0bb1da3d10635120dc67463a4602a735c089/src/sass/pages/_tuvandinhduong.scss

```
````html
<!-- filepath: c:\Users\User\Desktop\invitation\wedding.html -->
<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Ұл тойға шақыру - Имран, Ақмаль мен Әлинұрдың құрметіне арналған ұл тойы">
    <meta name="theme-color" content="#1a1a1a">
    
    <!-- Open Graph Tags -->
    <meta property="og:title" content="Ұл тойға шақыру">
    <meta property="og:description" content="Сіздерді ұлдарымыздың құрметіне арналған ұл тойымыздың қадірлі қонағы болуға шақырамыз!">
    <meta property="og:type" content="event">
    <meta property="og:image" content="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 1200 630'%3E%3Crect fill='%23d4af37' width='1200' height='630'/%3E%3Ctext x='600' y='315' font-size='48' text-anchor='middle' fill='%231a1a1a' font-family='serif'%3EҰл тойға шақыру%3C/text%3E%3C/svg%3E">
    
    <title>Ұл тойға шақыру | Tusau Kesew Celebration</title>
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --primary-gold: #d4af37;
            --dark-bg: #1a1a1a;
            --light-bg: #f9f7f4;
            --text-dark: #2d2d2d;
            --text-light: #f9f7f4;
            --accent-brown: #8b6f47;
            --accent-cream: #ede4d3;
        }

        @media (prefers-color-scheme: dark) {
            :root {
                --bg-primary: #1a1a1a;
                --bg-secondary: #2d2d2d;
                --text-primary: #f9f7f4;
                --text-secondary: #d4af37;
            }
        }

        @media (prefers-color-scheme: light) {
            :root {
                --bg-primary: #f9f7f4;
                --bg-secondary: #ede4d3;
                --text-primary: #2d2d2d;
                --text-secondary: #8b6f47;
            }
        }

        body {
            font-family: 'Georgia', 'Noto Serif', serif;
            background-color: var(--dark-bg);
            color: var(--text-light);
            line-height: 1.6;
            overflow-x: hidden;
        }

        @media (prefers-color-scheme: light) {
            body {
                background-color: var(--light-bg);
                color: var(--text-dark);
            }
        }

        /* Pattern Background */
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-image: 
                repeating-linear-gradient(45deg, transparent, transparent 35px, rgba(212, 175, 55, 0.03) 35px, rgba(212, 175, 55, 0.03) 70px);
            pointer-events: none;
            z-index: 0;
        }

        main {
            position: relative;
            z-index: 1;
        }

        /* Header */
        header {
            background: linear-gradient(135deg, rgba(26, 26, 26, 0.95) 0%, rgba(139, 111, 71, 0.95) 100%);
            padding: 3rem 2rem;
            text-align: center;
            border-bottom: 3px solid var(--primary-gold);
            animation: slideDown 0.8s ease-out;
        }

        @media (prefers-color-scheme: light) {
            header {
                background: linear-gradient(135deg, rgba(237, 228, 211, 0.98) 0%, rgba(212, 175, 55, 0.15) 100%);
                border-bottom: 3px solid var(--primary-gold);
            }
        }

        @keyframes slideDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .header-icon {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }

        h1 {
            font-size: 2.5rem;
            color: var(--primary-gold);
            margin-bottom: 0.5rem;
            font-weight: 400;
            letter-spacing: 1px;
        }

        .subtitle {
            font-size: 1rem;
            color: var(--accent-cream);
            font-style: italic;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 1.8rem;
            }
            
            .subtitle {
                font-size: 0.9rem;
            }

            header {
                padding: 2rem 1rem;
            }
        }

        /* Container */
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 3rem 2rem;
        }

        /* Greeting Section */
        .greeting {
            text-align: center;
            margin-bottom: 3rem;
            animation: fadeInUp 1s ease-out 0.2s both;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .greeting h2 {
            font-size: 1.8rem;
            color: var(--primary-gold);
            margin-bottom: 1.5rem;
            font-weight: 400;
        }

        .greeting p {
            font-size: 1.1rem;
            line-height: 1.8;
            color: var(--text-light);
            margin-bottom: 1rem;
        }

        @media (prefers-color-scheme: light) {
            .greeting p {
                color: var(--text-dark);
            }
        }

        /* Decorative Divider */
        .divider {
            width: 100px;
            height: 2px;
            background: linear-gradient(90deg, transparent, var(--primary-gold), transparent);
            margin: 2rem auto;
        }

        /* Event Details Box */
        .event-details {
            background: linear-gradient(135deg, rgba(212, 175, 55, 0.15) 0%, rgba(139, 111, 71, 0.1) 100%);
            border: 2px solid var(--primary-gold);
            border-radius: 8px;
            padding: 2.5rem;
            margin: 3rem 0;
            animation: fadeInUp 1s ease-out 0.4s both;
            position: relative;
            overflow: hidden;
        }

        .event-details::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='
```


## License: unknown
https://github.com/yemunhtetoo/m9updatedfile/blob/19f3db270ead6a272700fb0346fc62a766d47e97/css/pagetest.css

```
````html
<!-- filepath: c:\Users\User\Desktop\invitation\wedding.html -->
<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Ұл тойға шақыру - Имран, Ақмаль мен Әлинұрдың құрметіне арналған ұл тойы">
    <meta name="theme-color" content="#1a1a1a">
    
    <!-- Open Graph Tags -->
    <meta property="og:title" content="Ұл тойға шақыру">
    <meta property="og:description" content="Сіздерді ұлдарымыздың құрметіне арналған ұл тойымыздың қадірлі қонағы болуға шақырамыз!">
    <meta property="og:type" content="event">
    <meta property="og:image" content="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 1200 630'%3E%3Crect fill='%23d4af37' width='1200' height='630'/%3E%3Ctext x='600' y='315' font-size='48' text-anchor='middle' fill='%231a1a1a' font-family='serif'%3EҰл тойға шақыру%3C/text%3E%3C/svg%3E">
    
    <title>Ұл тойға шақыру | Tusau Kesew Celebration</title>
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --primary-gold: #d4af37;
            --dark-bg: #1a1a1a;
            --light-bg: #f9f7f4;
            --text-dark: #2d2d2d;
            --text-light: #f9f7f4;
            --accent-brown: #8b6f47;
            --accent-cream: #ede4d3;
        }

        @media (prefers-color-scheme: dark) {
            :root {
                --bg-primary: #1a1a1a;
                --bg-secondary: #2d2d2d;
                --text-primary: #f9f7f4;
                --text-secondary: #d4af37;
            }
        }

        @media (prefers-color-scheme: light) {
            :root {
                --bg-primary: #f9f7f4;
                --bg-secondary: #ede4d3;
                --text-primary: #2d2d2d;
                --text-secondary: #8b6f47;
            }
        }

        body {
            font-family: 'Georgia', 'Noto Serif', serif;
            background-color: var(--dark-bg);
            color: var(--text-light);
            line-height: 1.6;
            overflow-x: hidden;
        }

        @media (prefers-color-scheme: light) {
            body {
                background-color: var(--light-bg);
                color: var(--text-dark);
            }
        }

        /* Pattern Background */
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-image: 
                repeating-linear-gradient(45deg, transparent, transparent 35px, rgba(212, 175, 55, 0.03) 35px, rgba(212, 175, 55, 0.03) 70px);
            pointer-events: none;
            z-index: 0;
        }

        main {
            position: relative;
            z-index: 1;
        }

        /* Header */
        header {
            background: linear-gradient(135deg, rgba(26, 26, 26, 0.95) 0%, rgba(139, 111, 71, 0.95) 100%);
            padding: 3rem 2rem;
            text-align: center;
            border-bottom: 3px solid var(--primary-gold);
            animation: slideDown 0.8s ease-out;
        }

        @media (prefers-color-scheme: light) {
            header {
                background: linear-gradient(135deg, rgba(237, 228, 211, 0.98) 0%, rgba(212, 175, 55, 0.15) 100%);
                border-bottom: 3px solid var(--primary-gold);
            }
        }

        @keyframes slideDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .header-icon {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }

        h1 {
            font-size: 2.5rem;
            color: var(--primary-gold);
            margin-bottom: 0.5rem;
            font-weight: 400;
            letter-spacing: 1px;
        }

        .subtitle {
            font-size: 1rem;
            color: var(--accent-cream);
            font-style: italic;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 1.8rem;
            }
            
            .subtitle {
                font-size: 0.9rem;
            }

            header {
                padding: 2rem 1rem;
            }
        }

        /* Container */
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 3rem 2rem;
        }

        /* Greeting Section */
        .greeting {
            text-align: center;
            margin-bottom: 3rem;
            animation: fadeInUp 1s ease-out 0.2s both;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .greeting h2 {
            font-size: 1.8rem;
            color: var(--primary-gold);
            margin-bottom: 1.5rem;
            font-weight: 400;
        }

        .greeting p {
            font-size: 1.1rem;
            line-height: 1.8;
            color: var(--text-light);
            margin-bottom: 1rem;
        }

        @media (prefers-color-scheme: light) {
            .greeting p {
                color: var(--text-dark);
            }
        }

        /* Decorative Divider */
        .divider {
            width: 100px;
            height: 2px;
            background: linear-gradient(90deg, transparent, var(--primary-gold), transparent);
            margin: 2rem auto;
        }

        /* Event Details Box */
        .event-details {
            background: linear-gradient(135deg, rgba(212, 175, 55, 0.15) 0%, rgba(139, 111, 71, 0.1) 100%);
            border: 2px solid var(--primary-gold);
            border-radius: 8px;
            padding: 2.5rem;
            margin: 3rem 0;
            animation: fadeInUp 1s ease-out 0.4s both;
            position: relative;
            overflow: hidden;
        }

        .event-details::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='
```

