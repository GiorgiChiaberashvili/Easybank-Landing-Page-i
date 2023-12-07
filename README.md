# Frontend Mentor - EasyBank Landing Page Solution

This is a solution to the Easybank-landing-page

## Table of contents

  - [Screenshot](#screenshot)
  - [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Author](#author)

### Screenshot

![](./src/images/Screenshot%202023-12-07%20142809.png)
![](./src/images/Screenshot%202023-12-07%20142846.png)
![]()


## My process

Never giving up and keep pushing further like before, nothing changed.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox 
- React
- Grid
- and with bunch of Love.

### What I learned

HTML: Learned how to import SVG files in a different way.

CSS: Using fill element to modify color of SVG.

1) Text decoration underline was new feature that I learned. 

2) Ability to change color with decreasing opacity on the button is something new.

![](./src/images/Screenshot%202023-12-07%20143023.png)

React: Keep learning the logic behind the Hamburger functionality.

This is following logic behind hamburger order.

1) Setting the default usestate:

const [showModal, setShowModal] = useState(false);

2)  Setting Logic for show and not show

const handleModalShow = () => {
        setShowModal(!showModal)
    }

3) Applying the logic the icons

      <!-- {!showModal && <img src={hamburger} alt='hamburger' className={classes.hamburger} onClick={handleModalShow} />} -->

The above translates into the following: If  close icon is hidden show close icon on click

    <!-- {showModal && <img src={closeBtn} onClick={handleModalShow} className={classes.hamburger} alt='close' />} -->

The above translates into the following: In otherwise

       {showModal && <Modal />}

On click handle showing Modal

![](./src/images/Screenshot%202023-12-07%20145007.png)

![](./src/images/Screenshot%202023-12-07%20144443.png)


## Author

- Website - [Giorgi Chiaberashvili](https://giorgichiaberashvili.github.io/)


