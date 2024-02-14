<script setup>
import 'boxicons'

defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>


<template>
<link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <nav class="navigation">
        <a href="#" class = "logo">ConVerse</a>
        <div class="links">
            <a href="#">Home</a>
            <a href="#">Features</a>
            <a href="#">Blog</a>
            <a href="#">About us</a>
        </div>
        <div class="login">
            <button class="signup">Get started</button>
            <button>Login</button>
        </div>
    </nav>

    <header>
      <div class="left">
        <h1>Let's Buy Some <span>Converse</span></h1>
        <p>Lorem ipsum dolor sit amet consectetur. 
          Sit mi dictumst nisl imperdiet ornare arcu etiam. 
          Eleifend lorem bibendum integer est gravida.
        </p>
        <a href="#">
          <img class="img2" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAAAXNSR0IArs4c6QAAAhNJREFUaEPtmWtOxDAMhL03g5MBJ4ObwRo1UtY4mbFd0q3U/ls5aebzq+72Jie/bifXLxfA0RG8IiAinyLyISJfwWi8i8jbfW/JiaXNd8FNhGpXABak36d79HfqqgC8bN7vD2bE9OLb3rSO9MZNvEK0SyPwSrrx26xjwN1bZwE876t4tg68KKQgsgBauFnvN0/ukkoZAO/giPf7VCinUgbAHhrJfZvH5ShEAcoHOpVYikIEINs2UWMqOSUCsEfhjmDSUWABqm0zEwWqrbIA/+n9Ulv1ALycRB5cYXdnLQ/AenuFuMgZD5o9AFtQkZuvWAsBnjWF2sj+MDAyNVB50lYjYtP5z8gy6kI2jdhuVRVs91sdaQCqJ++s3j573EwYedbWwREA1LOHBVDnojRCaYfsNoAw/5Go6IFoPbL3AN7o4jpw5lXrAZRGSCCyzwCGnXAGEK0DJBDZewDaeTMAOozbyUggss9eNYevrNHCnL37IoHI3gBCjkMAkTRCApF9NFZPJ4EowOxmSCCyNwCqfbbFCEDXsQejdcjeNMHxoS+WDMConSKByK66qPEhChCpg+o4RI0PVQD0BK9AhPI/IoQJf0W4lz6UPqYG9Eb0k7FAEc5/inATdMRrJpq9fqWxEfDaacHZ1FZKG7XogCjQf9dHAFqh6ZfF/uMG5U5ykaaNXvRHvygAqWPdsgtgna/9k04fgR/Cq44xZ79E9QAAAABJRU5ErkJggg=="/>
          <span>Buy now</span>
        </a>
      </div>

      <img class="img1" src="../assets/c2.png">

    </header>

    <h2 class="separator">
      Buy your favourite converse
    </h2>

    <div class="buy-converse">
      <div class="item">
        <div class="header">
          <img class="wallet" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAAAXNSR0IArs4c6QAAAcFJREFUaEPtmAFuwyAMRd2TbTvZtpN1O9m2L81VQh34BsPIClKVSCXwn22w4SInb5eT65cF8NceXB5YHmi0wL8MoWcReRURPGdqHyLy/qMLz1uzPHCdULwKhviXEsDXTGY3tOyMbnngYQCiNwDWcCEeuIvFgLBj114IAHaDtwDR2yGw6wGi1JoBeohX0YwXmgCY0IEl8Xv6VYV3QKMxXkMf5KGjVgVgJhFjhtLk+ITxIMaBAaxk6gZgdxtGvDIzENo33Z26AHjEeyGGAKSTaMhBLN6PAFEW7GobIyy7A1jijsIu3WWYUBoOkBOV7vXMrtYdIDtBEhJTAqRhUYprDzD4u3vAA5CulynXQC6uU2tOAXBUhKk4zabWMZVJkt1DSGucXP1i1TWM9YesARXnycas+BAAzaafRDXJQDDiczcj7lpo635m8m3ZjLDSUgEGwHupdCidCZoA1Bu7q43SEcrxP+PBZgDoKSUrh+ZbV0Y8OocAMDWMF6IUOjpeCMCdJbxqibI59EgZoC9siDAPhClyDlQEYGPROW9Id+py9/TX6yGmGjUIUw2O0lI1zwKoMlvgR8sDgcasGmp5oMpsgR99Az1beTHxuX8IAAAAAElFTkSuQmCC"/>
          <h5>Connect Wallet</h5>
        </div>
        <p>
          Lorem ipsum dolor sit amet consectetur. 
          Sit mi dictumst nisl imperdiet ornare arcu etiam. 
          Eleifend lorem bibendum integer est gravida.
        </p>
      </div>

      <div class="item">
        <div class="header">
          <img class="wallet" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAAAXNSR0IArs4c6QAAAR9JREFUaEPtWcsOxCAIpP//0bvZpL1Y3XEYDWroFRXmAabtZZs/1+b1WwKIVrCmwIcsSlVRypcAzOQ+SgVKy5eMqB4nW+q1/G89PT1wDADJq2bm3T9MAW8Bjye8+xPA0wNeBpdVoGxuNL288WkWWhZAa257GWxZiCWgWhcz448DgG5YxDC7f7gCbAHqFEsAKoPqflkBZJmQODOFQgpESRMAYmh2nFFAbUL1IpSbOAEUFKKbussdXYvuxMcpoDKIeqKr/xUFlgXQYgYxhuLe70/LvJEtBwB5lLHn7yyX8syXOXUKIcAJAL18b68AssCs+LApNKtAdK4MACVgpw0ap1S+nilEHYgWV+JSbyWAFX/yOVwQt0VtwLjK78wJIFqCL86qcDHubj6nAAAAAElFTkSuQmCC"/>
          <h5>Connect Wallet</h5>
        </div>
        <p>
          Lorem ipsum dolor sit amet consectetur. 
          Sit mi dictumst nisl imperdiet ornare arcu etiam. 
          Eleifend lorem bibendum integer est gravida.
        </p>
      </div>

      <div class="item">
        <div class="header">
          <img class="wallet" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAAAXNSR0IArs4c6QAAAP1JREFUaEPtmFEOwiAQRLc305OpJ9ObaTexjRVQ8ZGwNMNXE7s482ZJ6E42+JoG128y0DtBJaAEIIHdttDBzE5POP7ce11mAeeciFIC996KC/9/NLPb6285A+50oR/Nh4t3E+vKGYhK30X/ZaD3QX8HutHzSwIyAA+SEoAAm5dXn4HmCuCGMgAB4nIlgBHCDZQABIjLqxPQVQIy11Vidy1U+8FDATRvIRmoPNRKgPZwJfDk9eYJUEG19TIwXAtd5wFShHloqdW+XuYiG0iGvLn2cPpuIuJK9H7q7yhD3mUa7fQ3k2kn3PuA4pRlACOEGygBCBCXKwGMEG4wfAIPkEc7MXQId8oAAAAASUVORK5CYII="/>
          <h5>Connect Wallet</h5>
        </div>
        <p>
          Lorem ipsum dolor sit amet consectetur. 
          Sit mi dictumst nisl imperdiet ornare arcu etiam. 
          Eleifend lorem bibendum integer est gravida.
        </p>
      </div>
    </div>

    <h2 class="separator">
      Super Hot sneakers
    </h2>

    <div class="shop-converse">
      <div class="category">
        <a href="#">Classic</a>
        <a href="#">Vinyl</a>
        <a href="#">Suede</a>
        <a href="#">Trending</a>
      </div>

      <div class="converse-list">
        <div class="item">
          <img class="img1" src="../assets/1.webp">
          <div class="info">
              <div class="info2">
                <h5>New fashion style</h5>
                <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAAAXNSR0IArs4c6QAAAd1JREFUaEPtmQtOwzAQRN2TUU4GnAw4GTAollxn1/vxmCgokSrR4s+82UmyTW/l5Mft5PrLBXB0Ba8KnLECr5vop1LK/ef1sb3/3P6u7zU2zMELB9Zoj7dmPZc3kQhB+Itr1VKeBSGR+QCpRg239ADArXen8HYYKlEdjYhv15CMeJBiAWQ3TvCqU4bVGAGMnMeiONq8I1412xZAdL5aiRHAl6DCk03ETQOx5mOeZoSoVQOQomNt3vL+2XwNoHcfUUEZI0frZgS+7iGZsNMrAUjZt072CFhkbG/kzghJWJ/hjPsRkaOxfRVSAOa1mKVWWKcH2JkpVaAv25EAZpz/JUB/DmSuIKxU9RVwRcg8cVjqHOuYFxQpQq7rr2NzxhDzfPTeyI6IkdSSuG5kcG62FZh1373/imZuhXisGWrmMEFrp1fGSfv+kWqntSjh8xUQmvj0F5pRV8iGSIlXc+XoSeoQRiXS4iMAq+I0JT4KwIaYFp8BYEFQxGcBZiFo4mcAshBU8bMAUQi6eAaAF2KJeBaABYH/Sw+FGfcQ6k9MkeeoFPHMClhtR3tzp4lfATCKE7t/+jVl1RM39xcSoe8KfbQKoK8ENTYt4UqAkJPZwRdA1jnWvKsCLCez65y+At8NZYYxvongZAAAAABJRU5ErkJggg=="/>
              </div>
              <div class="info3">
                <div class="price">
                  <img class="img2" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAAAXNSR0IArs4c6QAAAfNJREFUaEPtmU0uBEEUgL/ZOIUl92BHWIhz4AqIE+Aswg5bZ3AGF5BgXhiZmVR1vXo/zSRTm1nM6+7ve6+q+lV6woqPyYrzsxb46wr2VGAHOAfkVzOegOdp4IUm2BqjFRAIgbeMy0wJjYAHfiacJtESiIBPlRgSqMFrsum5tmua1gQiACLu0ZQpCUQ+OPJeRZmSwGNhq9RMm1q2UiVKAp9LJB742a3SJDQCtXWyCRwB28Ab8ALcD0zaFAmrgMBfA8dzwK/AKfAwpoRV4AS4LYDeAYeNrSO0ElYByf5ZBbT1cpTLwiSsAtIXlZq0d2CjuXl/B4RIWAX2gRtgaw724wfqSikQImEVkIfvAbIWDgDJvID3wIdssR6BjkQ3Q83TSSMQ8SJrGljXxBithAbePJ1KAnJklH5oefzLSmS20z2ZX46trYndaaMpZ+3fkXWg8cAPTSeBFwmVQMg+7TCpVWEh6aO+9jtk1NuqRmDsSqjhBUwrMJZEF3yvQLZEN7xFIEvCBG8ViJYww3sEoiRc8F4Br4QbPkLAKhECHyXQKxEGHymglQiFjxZoScj/pY8krja9502sbWV6vim44DMqMNQKLyfADZ8pMDSd5L8Q+GyBmkQY/BgC8xJymhL4hSOhdmHV4jIWsZep6/q1QFe6EoJXvgJfIyiXMePv4vIAAAAASUVORK5CYII="/>
                  <p>200$</p>
                </div>
                <p>2 of 15</p>
              </div>
          </div>
        </div>

        <div class="item">
          <img class="img1" src="../assets/2.jpeg">
          <div class="info">
              <div class="info2">
                <h5>New fashion style</h5>
                <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAAAXNSR0IArs4c6QAAAd1JREFUaEPtmQtOwzAQRN2TUU4GnAw4GTAollxn1/vxmCgokSrR4s+82UmyTW/l5Mft5PrLBXB0Ba8KnLECr5vop1LK/ef1sb3/3P6u7zU2zMELB9Zoj7dmPZc3kQhB+Itr1VKeBSGR+QCpRg239ADArXen8HYYKlEdjYhv15CMeJBiAWQ3TvCqU4bVGAGMnMeiONq8I1412xZAdL5aiRHAl6DCk03ETQOx5mOeZoSoVQOQomNt3vL+2XwNoHcfUUEZI0frZgS+7iGZsNMrAUjZt072CFhkbG/kzghJWJ/hjPsRkaOxfRVSAOa1mKVWWKcH2JkpVaAv25EAZpz/JUB/DmSuIKxU9RVwRcg8cVjqHOuYFxQpQq7rr2NzxhDzfPTeyI6IkdSSuG5kcG62FZh1373/imZuhXisGWrmMEFrp1fGSfv+kWqntSjh8xUQmvj0F5pRV8iGSIlXc+XoSeoQRiXS4iMAq+I0JT4KwIaYFp8BYEFQxGcBZiFo4mcAshBU8bMAUQi6eAaAF2KJeBaABYH/Sw+FGfcQ6k9MkeeoFPHMClhtR3tzp4lfATCKE7t/+jVl1RM39xcSoe8KfbQKoK8ENTYt4UqAkJPZwRdA1jnWvKsCLCez65y+At8NZYYxvongZAAAAABJRU5ErkJggg=="/>
              </div>
              <div class="info3">
                <div class="price">
                  <img class="img2" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAAAXNSR0IArs4c6QAAAfNJREFUaEPtmU0uBEEUgL/ZOIUl92BHWIhz4AqIE+Aswg5bZ3AGF5BgXhiZmVR1vXo/zSRTm1nM6+7ve6+q+lV6woqPyYrzsxb46wr2VGAHOAfkVzOegOdp4IUm2BqjFRAIgbeMy0wJjYAHfiacJtESiIBPlRgSqMFrsum5tmua1gQiACLu0ZQpCUQ+OPJeRZmSwGNhq9RMm1q2UiVKAp9LJB742a3SJDQCtXWyCRwB28Ab8ALcD0zaFAmrgMBfA8dzwK/AKfAwpoRV4AS4LYDeAYeNrSO0ElYByf5ZBbT1cpTLwiSsAtIXlZq0d2CjuXl/B4RIWAX2gRtgaw724wfqSikQImEVkIfvAbIWDgDJvID3wIdssR6BjkQ3Q83TSSMQ8SJrGljXxBithAbePJ1KAnJklH5oefzLSmS20z2ZX46trYndaaMpZ+3fkXWg8cAPTSeBFwmVQMg+7TCpVWEh6aO+9jtk1NuqRmDsSqjhBUwrMJZEF3yvQLZEN7xFIEvCBG8ViJYww3sEoiRc8F4Br4QbPkLAKhECHyXQKxEGHymglQiFjxZoScj/pY8krja9502sbWV6vim44DMqMNQKLyfADZ8pMDSd5L8Q+GyBmkQY/BgC8xJymhL4hSOhdmHV4jIWsZep6/q1QFe6EoJXvgJfIyiXMePv4vIAAAAASUVORK5CYII="/>
                  <p>200$</p>
                </div>
                <p>2 of 15</p>
              </div>
          </div>
        </div>

        <div class="item">
          <img class="img1" src="../assets/3.webp">
          <div class="info">
              <div class="info2">
                <h5>New fashion style</h5>
                <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAAAXNSR0IArs4c6QAAAd1JREFUaEPtmQtOwzAQRN2TUU4GnAw4GTAollxn1/vxmCgokSrR4s+82UmyTW/l5Mft5PrLBXB0Ba8KnLECr5vop1LK/ef1sb3/3P6u7zU2zMELB9Zoj7dmPZc3kQhB+Itr1VKeBSGR+QCpRg239ADArXen8HYYKlEdjYhv15CMeJBiAWQ3TvCqU4bVGAGMnMeiONq8I1412xZAdL5aiRHAl6DCk03ETQOx5mOeZoSoVQOQomNt3vL+2XwNoHcfUUEZI0frZgS+7iGZsNMrAUjZt072CFhkbG/kzghJWJ/hjPsRkaOxfRVSAOa1mKVWWKcH2JkpVaAv25EAZpz/JUB/DmSuIKxU9RVwRcg8cVjqHOuYFxQpQq7rr2NzxhDzfPTeyI6IkdSSuG5kcG62FZh1373/imZuhXisGWrmMEFrp1fGSfv+kWqntSjh8xUQmvj0F5pRV8iGSIlXc+XoSeoQRiXS4iMAq+I0JT4KwIaYFp8BYEFQxGcBZiFo4mcAshBU8bMAUQi6eAaAF2KJeBaABYH/Sw+FGfcQ6k9MkeeoFPHMClhtR3tzp4lfATCKE7t/+jVl1RM39xcSoe8KfbQKoK8ENTYt4UqAkJPZwRdA1jnWvKsCLCez65y+At8NZYYxvongZAAAAABJRU5ErkJggg=="/>
              </div>
              <div class="info3">
                <div class="price">
                  <img class="img2" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAAAXNSR0IArs4c6QAAAfNJREFUaEPtmU0uBEEUgL/ZOIUl92BHWIhz4AqIE+Aswg5bZ3AGF5BgXhiZmVR1vXo/zSRTm1nM6+7ve6+q+lV6woqPyYrzsxb46wr2VGAHOAfkVzOegOdp4IUm2BqjFRAIgbeMy0wJjYAHfiacJtESiIBPlRgSqMFrsum5tmua1gQiACLu0ZQpCUQ+OPJeRZmSwGNhq9RMm1q2UiVKAp9LJB742a3SJDQCtXWyCRwB28Ab8ALcD0zaFAmrgMBfA8dzwK/AKfAwpoRV4AS4LYDeAYeNrSO0ElYByf5ZBbT1cpTLwiSsAtIXlZq0d2CjuXl/B4RIWAX2gRtgaw724wfqSikQImEVkIfvAbIWDgDJvID3wIdssR6BjkQ3Q83TSSMQ8SJrGljXxBithAbePJ1KAnJklH5oefzLSmS20z2ZX46trYndaaMpZ+3fkXWg8cAPTSeBFwmVQMg+7TCpVWEh6aO+9jtk1NuqRmDsSqjhBUwrMJZEF3yvQLZEN7xFIEvCBG8ViJYww3sEoiRc8F4Br4QbPkLAKhECHyXQKxEGHymglQiFjxZoScj/pY8krja9502sbWV6vim44DMqMNQKLyfADZ8pMDSd5L8Q+GyBmkQY/BgC8xJymhL4hSOhdmHV4jIWsZep6/q1QFe6EoJXvgJfIyiXMePv4vIAAAAASUVORK5CYII="/>
                  <p>200$</p>
                </div>
                <p>2 of 15</p>
              </div>
          </div>
        </div>

        <div class="item">
          <img class="img1" src="../assets/1.webp">
          <div class="info">
              <div class="info2">
                <h5>New fashion style</h5>
                <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAAAXNSR0IArs4c6QAAAd1JREFUaEPtmQtOwzAQRN2TUU4GnAw4GTAollxn1/vxmCgokSrR4s+82UmyTW/l5Mft5PrLBXB0Ba8KnLECr5vop1LK/ef1sb3/3P6u7zU2zMELB9Zoj7dmPZc3kQhB+Itr1VKeBSGR+QCpRg239ADArXen8HYYKlEdjYhv15CMeJBiAWQ3TvCqU4bVGAGMnMeiONq8I1412xZAdL5aiRHAl6DCk03ETQOx5mOeZoSoVQOQomNt3vL+2XwNoHcfUUEZI0frZgS+7iGZsNMrAUjZt072CFhkbG/kzghJWJ/hjPsRkaOxfRVSAOa1mKVWWKcH2JkpVaAv25EAZpz/JUB/DmSuIKxU9RVwRcg8cVjqHOuYFxQpQq7rr2NzxhDzfPTeyI6IkdSSuG5kcG62FZh1373/imZuhXisGWrmMEFrp1fGSfv+kWqntSjh8xUQmvj0F5pRV8iGSIlXc+XoSeoQRiXS4iMAq+I0JT4KwIaYFp8BYEFQxGcBZiFo4mcAshBU8bMAUQi6eAaAF2KJeBaABYH/Sw+FGfcQ6k9MkeeoFPHMClhtR3tzp4lfATCKE7t/+jVl1RM39xcSoe8KfbQKoK8ENTYt4UqAkJPZwRdA1jnWvKsCLCez65y+At8NZYYxvongZAAAAABJRU5ErkJggg=="/>
              </div>
              <div class="info3">
                <div class="price">
                  <img class="img2" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAAAXNSR0IArs4c6QAAAfNJREFUaEPtmU0uBEEUgL/ZOIUl92BHWIhz4AqIE+Aswg5bZ3AGF5BgXhiZmVR1vXo/zSRTm1nM6+7ve6+q+lV6woqPyYrzsxb46wr2VGAHOAfkVzOegOdp4IUm2BqjFRAIgbeMy0wJjYAHfiacJtESiIBPlRgSqMFrsum5tmua1gQiACLu0ZQpCUQ+OPJeRZmSwGNhq9RMm1q2UiVKAp9LJB742a3SJDQCtXWyCRwB28Ab8ALcD0zaFAmrgMBfA8dzwK/AKfAwpoRV4AS4LYDeAYeNrSO0ElYByf5ZBbT1cpTLwiSsAtIXlZq0d2CjuXl/B4RIWAX2gRtgaw724wfqSikQImEVkIfvAbIWDgDJvID3wIdssR6BjkQ3Q83TSSMQ8SJrGljXxBithAbePJ1KAnJklH5oefzLSmS20z2ZX46trYndaaMpZ+3fkXWg8cAPTSeBFwmVQMg+7TCpVWEh6aO+9jtk1NuqRmDsSqjhBUwrMJZEF3yvQLZEN7xFIEvCBG8ViJYww3sEoiRc8F4Br4QbPkLAKhECHyXQKxEGHymglQiFjxZoScj/pY8krja9502sbWV6vim44DMqMNQKLyfADZ8pMDSd5L8Q+GyBmkQY/BgC8xJymhL4hSOhdmHV4jIWsZep6/q1QFe6EoJXvgJfIyiXMePv4vIAAAAASUVORK5CYII="/>
                  <p>200$</p>
                </div>
                <p>2 of 15</p>
              </div>
          </div>
        </div>
      </div>
    </div>

<div class="view-more">
  <button>View more</button>
</div>

<h2 class="separator">
      Custom
</h2>

<div class="sellers">
  <div class="item">
    <img src="../assets/custom1.webp">
    <div class="info">
      <h4>Adam Smith</h4>
      <p>1,5k</p>
    </div>
  </div>

  <div class="item">
    <img src="../assets/custom2.jpeg">
    <div class="info">
      <h4>Raya Serw</h4>
      <p>2k</p>
    </div>
  </div>

  <div class="item">
    <img src="../assets/custom3.webp">
    <div class="info">
      <h4>Frodo Martini</h4>
      <p>0,5k</p>
    </div>
  </div>

  <div class="item">
    <img src="../assets/custom4.webp">
    <div class="info">
      <h4>Zak Luck</h4>
      <p>1k</p>
    </div>
  </div>
</div>

<footer>
  <h3>Collect & Save Sneakers</h3>
  <div class="right">
    <div class="links">
      <a href="#">Privacy polici</a>
      <a href="#">Cooperation</a>
      <a href="#">Sponsorship</a>
      <a href="#">Contact Us</a>
    </div>
    <div class="social">
      <i class='bx bxl-instagram'></i>
      <i class='bx bxl-facebook-square'></i>
      <i class='bx bxl-github' ></i>
    </div>
    <p>Copyright 2024 ConVerse, All Rights Reserved</p>
  </div>
</footer>
</template>

<style scoped>

.navigation{
    padding: 0 80px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    height: 80px;
    
}

.logo{
  font-size: 33px;
  font-weight: 600;
}

.links a{
  margin-right: 20px;
}

.navigation .login button{
  padding: 8px 14px;
  border: none;
  background-color: transparent;
  cursor: pointer;
}

.navigation .login button.signup{
  background-color: #000;
  color:#fff;
  border-radius: 4px;
  margin-right: 14px;
}

header{
  padding: 0 80px;
  height: calc(100vh - 80px);
  display: flex;
  align-items: center;
  justify-content: space-between;
}

header .left{
  width: 700px;
}

header .img1{
  width: 700px;

}

@media only screen and (max-width: 1400px) {
  nav,
  header,
  h2.separator,
  .buy-converse,
  .shop-converse,
  .sellers{
    padding: 0 80px;
  }
  


}


header .left h1{
  font-size: 80px;
}
header .left span{
  color: rgb(111, 120, 149);
}

header .left .img2{
  width: 30px;
  background-color: #fff;
  border-radius: 50%;
  padding: 3px;
}

header .left p{
  margin: 40px 0;
  color: rgb(159, 161, 163);
}

header .left a{
  display: flex;
  align-items: center;
  background-color: #000;
  width: 200px;
  padding: 8px;
  border-radius: 60px;
}
header .left a span{
  color: #fff;
  margin-left: 10px;
}

.separator{
  padding: 0 80px;
  font-size: 40px;
  margin-top: 40px;
}

.buy-converse{
  padding: 0 80px;
  margin: 50px 0 80px;
  display: flex;
  justify-content: space-between;
  gap: 30px;
}

.buy-converse .item,
.shop-converse .converse-list .item{
  padding: 20px;
  background-color: #ffffffd4;
  border-radius: 16px;
  box-shadow: 0 10px 30px rgba(15, 0, 98, 0.1);
  transition: all 0.3s ease;
  cursor: pointer;
}

.buy-converse .item:hover,
.shop-converse .converse-list .item:hover,
.sellers .item:hover{
  box-shadow: none;
}

.buy-converse .item .header{
  display: flex;
  align-items:center;
  gap: 10px;
}

.buy-converse .item .header .wallet{
  /* margin: 5px; */
}

.buy-converse .item .header h5{
  font-size: 18px;
}

.buy-converse .item p{
  margin-top: 10px;
  padding:  0 4px;
}

.shop-converse{
  padding: 0 80px;
  margin-top: 30px;
}
.shop-converse .category{
  display: flex;
  gap: 14px;
}

.shop-converse .category a{
  background-color: #ebebeb;
  padding: 8px 14px;
  font-size: 14px;
  border-radius: 14px;
  transition: all 0.3s ease;
}

.shop-converse .category a:hover{
  color: #ebebeb;
  background-color: #000;
}

.shop-converse .converse-list{
  padding: 40px 0;
  display: flex;
  flex-flow: row wrap;
  width: 100%;
  justify-content: space-between;
  gap: 20px;
}

.shop-converse .converse-list .item .img1{
  width: 280px;
  height: 280px;
  border-radius: 18px;
  
}

.shop-converse .converse-list .item .info{
  display: flex;
  flex-flow: column nowrap;
  /* align-items: flex-end; */
  justify-content: space-between;
  margin-top: 16px;
}

.shop-converse .converse-list .item .info h5{
  font-size: 18px;
}

.shop-converse .converse-list .item .info .price{
  margin-top: 10px;
  display: flex;
  align-items: center;
  gap: 5px;
}

.shop-converse .converse-list .item .info .price p{
  font-size: 30px;
  color: #536392d4;
}

.shop-converse .converse-list .item .info .price .img2{
  width: 20px;
}
.shop-converse .converse-list .item .info .info2{
  display: flex;
  flex-flow: row nowrap;
  align-items: center;
  justify-content: space-between;
  width: auto;
}
.shop-converse .converse-list .item .info .info3{
  display: flex;
  flex-flow: row nowrap;
  align-items: flex-end;
  justify-content: space-between;
  width: auto;


}

.shop-converse .converse-list .item .info > p{
  font-size: 15px;
  color: #a2a2a2;
}

.shop-converse .converse-list .item .info .info2 img{
  width: 30px;
}

.view-more{
  margin: 10px 0 40px;
  display: flex;
  justify-content: center;
}

.view-more button{
  padding: 10px 20px;
  font-size: 16px;
  border: none;
  background-color: #e0e0e0;
  border-radius: 10px;
  cursor: pointer;
  transition: all 0.3s ease;
}

.view-more button:hover{
  color: #ebebeb;
  background-color: #000;
}

.sellers{
  padding: 0 80px;
  margin: 40px 0 80px;
  display: flex;
  gap: 30px;
}

.sellers .item img{
  height: 60px;
  width: 60px; 
}

.sellers .item{
  background-color: #ffffff;
  display: flex;
  align-items: center;
  width: 25%;
  gap: 14px;
  padding: 14px;
  border-radius: 18px;
  cursor: pointer;
  box-shadow: 0 10px 30px rgba(15, 30, 42, 0.1);
  transition: all 0.3s ease;
}

footer{
  background-color: #000;
  color: #fff;
  padding: 100px 80px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

footer h3{
  font-size: 48px;
}

footer .right{
  width: 80%;
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  gap: 26px;
}

footer .right .links{
  display: flex;
  gap: 30px;
}

footer .right .links a{
  color:#aeaeae;
  transition: all 0.3s ease;
}

footer .right .links a:hover{
  color: #fff;
}

footer .right .social{
  display: flex;
  align-items: center;
  gap: 10px;
}

footer .right .social i{
  font-size: 30px;
  cursor: pointer;
  transition: color 0.3s ease;
}

footer .right .social i:hover{
  color: #a2a2a2;
}

footer .right p{
  font-size: 14px;
  color: #a2a2a2;
}

@media only screen and (max-width: 1400px){
  header .left h1{
    font-size: 48px;
  }
  header .img1{
    width: 480px;
  }
  h2.separator{
    font-size: 34px;
  }
  .buy-converse .item .header .wallet{
     font-size: 36px;
  }

  .buy-converse .item .header h5{
    font-size: 15px;
  }

  .buy-converse .item p{
    font-size: 13px;
  }

  .shop-converse .converse-list{
    flex-wrap: wrap;
    row-gap: 30px;
  }

  .shop-converse .converse-list .item{
    width: 48%;
  }
  .shop-converse .converse-list .item .img1{
    width: 100%;

  }

  .sellers{
    flex-wrap: wrap;
  }

  .sellers .item{
    width: 48%;
  }

  footer .links a{
    font-size: 15px;
  }
}

@media only screen and (max-width: 992px){
  nav a.logo{
    font-size: 28px;
  }

  nav .links a{
    font-size: 14px;
  }

  header{
    flex-direction: column-reverse;
    height: auto;
    margin-bottom: 60px;
  }

  header .left{
    width: 100%;
  }

  header .img1{
    padding:  40px;
    width: 90%;
  }
  .buy-converse{
    flex-wrap: wrap;
    gap: 20px;
  }

  .buy-converse .item{
    width: 48%;
  }

  .sellers{
    gap: 20px;
  }

  footer{
    flex-direction: column;
    padding: 60px 40px;
  }

  footer h3{
    margin-bottom: 40px;
    font-size: 32px;
  }

  footer .right{
    width: 100%;
    align-items: center;
  }
}

@media only screen and (max-width: 768px){
  nav,
  header,
  h2.separator,
  .buy-converse,
  .shop-converse,
  .sellers{
    padding: 0 20px;
  }

  nav a.logo{
    display: none;
  }

  nav .links a{
    font-size: 12px;
  }

  nav .login button{
    font-size: 12px;
    padding: 6px 10px;
  }

  header .left h1{
    font-size: 36px;
  }

  header .left p{
    font-size: 14px;
  }

  header .left a{
    padding: 6px;
    width: 160px;
    font-size: 14px;
  }

  header .left .img2{
    padding: 6px;
  }

  h2.separator{
    font-size: 30px;
  }

  footer{
    padding: 40px 20px;
  }
}
@media only screen and (max-width: 576px){
  header .left h1{
    font-size: 30px;
  }

  .buy-converse .item{
    width: 100%;
  }

  .shop-converse .converse-list .item,
  .sellers .item{
    width: 47%;
  }

  .shop-converse .category a{
    font-size: 13px;
  }
}

</style>
