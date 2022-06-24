1. css variables(custom properties) also cascades and inherites.
   Also, they can be manipulated in js.
2. align-items დიფოლტი სტრეჩ არის და ცენტრზე გადაყვანისას, გაწელილი
   ჰეითი აღარ ექნება.
3. ინფუტები არ აინჰერითებენ ფონტ ფემილის და ფონტ საიზს ავტომატურად და
   ხელით უნდა დავუსეტოთ. მგონი ქოლორსაც არ აინჰერითებს.
4. > დაირექთ ჩილდრენებს ასელექთებს.
5. align-self align-item - ის მსგავსად მუშაობს, მაგრამ ერთ აითემზე ვიყენებთ.
6. ფლქსბოქსები შვილ ელემენტებზე კიარ მუშაობს only, არამედ
   ტექსტებზეც მუშაობს. სპანშიც ტექსტი თუ გვაქვს, მაგალიტად, შეგვიძლია
   ეს სპანი გავფლექსოთ და ჯასთიფაი კონტენტით და ელაიგნ აითემით გავცენტროთ.
7. https://icomoon.io/app
8. currentColor is the color of the current element or the parent element.
   ასევე რასაც ჰოვერზე დავუყენებთ ფერს მშობელს, შვილის ქარენთ ქოლორი ავტომატურად
   დაჯდება და ზედმეტი კოდის წერა არ მოგვიწევს.
9. before ისთვის ფერენთ ელემენტი არის იგივე ელემენტი, რომელსაც ედება.
10. ზ-ინდექსი მაშინ მუშაობს, როცა ფოსიშენი გვაქვს დასეტილი.
11. transition: width 0.4s cubic-bezier(1, 0, 0, 1) 0.2s, აქ ბოლო არგუმენტი დილეია.
12. სურათი რომ რესპონსიული იყოს და ფლუიდური, img ელემენტის width პროცენტებშ უნდა
    დავსეტოთ ხოლმე.
13. image should always be block or inline-block if we do not want white space.
14. margin-right: auto; კარგი თრიქია რომ ელემენტს ფლექსის გამოყენებისას, თავისი ზომა
    მივაღებინოთ, მაგრამ ადგილი ქონდეს მარჯვინ ცარიელი.
15. :not(:last-child) ბოლო ელემენტის გარდა ყველა შვილს ასელექთებს, მაგრამ
    :not(:last-of-type) იმავე ტიპის ბოლო ელემენტის გარდა და რაღაც დროს
    ლასთ ოფ თაიფ შეიძლება გვჭირდებოდეს.
16. Basically masks defines area where we can look through the
    element and see what is behind that element.
    In our case, what we are gonna do is to set the background-color
    of this element to a solid color, and then use the icon as the mask.
    And so we can then look through that mask and see the background color in the area where the icon is and everything else is covered,
    and so it is just gonna be white. ეს ფიჩერი იმიტომ გამოვიყენეთ,
    რადგან ბექრაუნდ იმიჯით ფერის შეცვლა არ შეგვიძლია და ჩვენ რადგანაც
    ესვიჯის ვსეტავდით ბექრაუნდზე და ფერის შეცვლაც გვინდოდა,
    მაგიტომ გამოვიყენეთ მასკი.
17. What border-box does is that it includes the padding and the border
    into the width and height of the element.
    box-sizing: content-box; კი პადინგს და მარჯინს ზემოდან ამატებს, თავის საიზებში არ შეყავს.
    ანუ დიფოლტზე გადაყავს.
18. https://css-tricks.com/snippets/html/glyphs/
19. transition does not work for background-image and for gradients.
