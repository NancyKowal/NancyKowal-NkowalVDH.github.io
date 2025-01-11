# NancyKowal-NkowalVDH.github.io
website Fred 
breakpoints : 600px, 900px, 1200px en plu

.section-how {
  padding: 10rem 0 ;
  max-width: 130rem;
}

.container-how {
  /* 1140px is also ver0y much used */
  max-width: 140rem;
  margin: 0 auto;
  align-items: center;
  border-top: rgba(66, 136, 150, 0.068) solid 0.1rem;
  border-bottom: rgba(66, 136, 150, 0.055) solid 0.1rem;
  overflow: hidden;
}
.step-text-box {
  display: grid;
  grid-template-rows: 1fr 1fr 1.5fr;
  column-gap: 1rem;
  justify-items: center;
  align-items: center;
}

.step-number {
  font-size: 9.8rem;
  font-weight: 500;
  color: rgba(230, 125, 34, 0.208);
  /* margin-bottom: 1rem; */
}

/* .step-text-box { 
  display: flex;
  align-items: center;
  flex-direction: column;
  position: relative;
}*/

.step-img-box img {
  height: 15rem;
  width: 15rem;
  border-radius: 10%;
  border: 3px solid #c6daee;
}

.step-img-box img:hover {
  transform: scale(1.1);
}

.tel,
.email:link,
.tel,
.email:visited {
  text-decoration: none;
  font-size: 2rem;
  color: rgba(230, 125, 34, 0.502);
  transition: all 0.3s;
}

.tel,
.email:hover,
.tel,
.email:active {
  color: rgba(230, 125, 34, 0.502);
}