# What I learn
## note
1. effect กระจก
```css
        /*เอฟเฟก กระจก*/
        .feature-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.1), transparent);
            transition: left 0.5s;
        }

        .feature-card:hover::before {
            left: 100%;
        }
        /*------------------*/
```
