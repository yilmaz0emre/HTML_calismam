EMMET KULLANIMI

    etiket isimlerini direk verebiliyoruz
    + kardes oge
    > icinde oge
    ^ yukari cik ve oge olustur
    * carp -> p*3
    lorem ???
    . -> class
    # -> id
    $ -> sıralama yapar

    kardes oge ornegi;

    h1+p+p+p+h2+p+p+p+p
    <h1></h1>
    <p></p>
    <p></p>
    <p></p>
    <h2></h2>
    <p></p>
    <p></p>
    <p></p>
    <p></p>

    carp ornegi;

    h1+p+p+p+h2+p+p+p+p -> h1+p*3+h2+p*4

    icinde oge ornegi;

    ul>li*2
    <ul>
        <li></li>
        <li></li>
    </ul>

    yukarı cık ve oge olustur;

    ul>li*2^p

    <ul>
        <li></li>
        <li></li>
    </ul>
    <p></p>

    lorem ornegi;

    lorem anlamsız yazılar
    lorem yazarsak çok uzun yazı olusur
    lorem4 -> 4 kelimelik yazı olusur
    p>lorem

    . ornegi;

    h3.denem
    <h3 class="deneme"></h3>
    h3.birinci-class.ikinci-class
    <h3 class="birinci-class ikinci-class"></h3>

    # ornegı;

    h3#idolussun>lorem3
    <h3 id="idolussun">Lorem, ipsum dolor.</h3>

    h3.deneme#idolussun>lorem1
    <h3 class="deneme" id="idolussun">Lorem.</h3>

    $ ornegi;

    ul>li.item$*4
    <ul>
        <li class="item1"></li>
        <li class="item2"></li>
        <li class="item3"></li>
        <li class="item4"></li>
    </ul>




    ÖRNEK;

    div tagı altında "item" id'sine sahip 10 kelimelik loremleri içeren 6 adet p tagı oluşturmak istersek

    div>p#item$*6>lorem10 

    <div>
        <p id="item1">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aperiam, cupiditate!</p>
        <p id="item2">Inventore voluptatibus tenetur quam magni ab placeat maiores optio aliquid.</p>
        <p id="item3">Ad unde, animi in quam impedit quidem temporibus ipsam sequi.</p>
        <p id="item4">Ut ipsam nisi sequi deleniti consequatur quas aut distinctio dolore?</p>
        <p id="item5">Odit molestias corporis repellat. Voluptate cumque nam deleniti earum odio!</p>
        <p id="item6">Odit doloribus blanditiis consequuntur eum. Dolores eligendi quae qui. Vero.</p>
    </div>



 Lorem ornegi;

    ul>li*2>lorem2^^p*2>lorem5^h5>lorem3

    <ul>
        <li>Lorem, ipsum.</li>
        <li>Id, harum.</li>
    </ul>
    <p>Lorem ipsum dolor sit amet.</p>
    <p>Nesciunt explicabo minima fuga possimus!</p>
    <h5>Lorem, ipsum dolor.</h5>
