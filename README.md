![](./banner/Sliding_menu_%2B_scss.png)

# slidingMenu

This is my private practicing of `HTML`, `CSS` and preporcessor `SCSS`

---

Frankly speaking, this case was a real challenge for as per working out of **sliding cards** 

I didn't managed to find solution for pushing cards sibling elements.

Another diffculty I faced on *nesting* of elemnts while using preprocessor `scss`.
I had to apply initial selectors from `HTML` as follows:
    
        &__list-item:hover .menu__list-item_slided {
            width: 30em;
        }
        
---

I also came to know that `transition` doesn't work along with `display: none` property.

I found solution for this with property `position` and its other values.
