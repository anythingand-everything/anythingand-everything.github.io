.home-container {
  width: 100%;
  height: auto;
  display: flex;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.home-hero {
  width: 100%;
  display: flex;
  max-width: 1320px;
  padding-left: var(--dl-space-space-unitandahalfunit);
  padding-right: var(--dl-space-space-unitandahalfunit);
  justify-content: center;
}
.home-container1 {
  width: 100%;
  display: flex;
  position: relative;
  max-width: 1320px;
  min-height: 85vh;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.home-card {
  flex: 0 0 auto;
  width: 60%;
  display: flex;
  padding: var(--dl-space-space-tripleunit);
  z-index: 1;
  box-shadow: 0 8px 26px -4px hsla(0,0%,8%,.15),0 8px 9px -5px hsla(0,0%,8%,.06)!important;
  margin-top: var(--dl-space-space-tripleunit);
  align-items: flex-start;
  border-radius: var(--dl-radius-radius-radius1);
  flex-direction: column;
  backdrop-filter: saturate(200%) blur(30px);
  background-color: hsla(0,0%,100%,.8);
}
.home-text {
  text-align: center;
  background-image: linear-gradient(310deg,#7928ca,#ff0080);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
.home-text1 {
  color: var(--dl-color-secondary-600);
  margin-right: var(--dl-space-space-tripleunit);
  margin-bottom: var(--dl-space-space-unit);
  padding-right: var(--dl-space-space-tripleunit);
}
.home-image {
  top: 0px;
  left: auto;
  right: 0px;
  width: 50%;
  bottom: 0px;
  height: 80vh;
  position: absolute;
  object-fit: cover;
  object-position: right;
  border-bottom-left-radius: 10rem;
}
.home-testimonials {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
  background-image: linear-gradient(310deg,#7928ca,#ff0080);
}
.home-image1 {
  top: auto;
  left: 0px;
  right: 0px;
  width: 100%;
  bottom: auto;
  height: 100%;
  position: absolute;
  object-fit: cover;
}
@media(max-width: 991px) {
  .home-hero {
    padding-left: var(--dl-space-space-tripleunit);
    padding-right: var(--dl-space-space-tripleunit);
  }
  .home-container1 {
    max-width: 960px;
  }
  .home-card {
    width: 100%;
  }
}
@media(max-width: 767px) {
  .home-card {
    align-items: center;
  }
  .home-text1 {
    text-align: center;
    margin-right: 0px;
    padding-right: 0px;
  }
  .home-image {
    display: none;
  }
}
@media(max-width: 479px) {
  .home-card {
    padding: var(--dl-space-space-unit);
  }
}
