
let menu = document.querySelector(".menu__lines"),
    nav = document.querySelector(".Navigation"),
    menuItem = document.querySelectorAll(".Navigation__list-item");


menuItem.forEach((e, t) => {
    e.addEventListener("click", function () {
        toggleMenu();
    });
}),
    menu.addEventListener("click", () => {
        toggleMenu();
    });
const toggleMenu = () => {
    menu.classList.toggle("show");
    nav.classList.toggle('showNav')
};

AOS.init({
  delay: 150,
  duration: 1300,
  easing: 'ease',
  once: true
})
