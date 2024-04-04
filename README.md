https://akashmagar703.github.io/jiograph1/


https://codepen.io/akashmagar703-the-lessful/pen/oNOEvoo
body {
  margin: 0;
  padding: 0;
  font-family: "Times New Roman", Times, serif;
}
.start1 img {
  width: 100%;
  height: 100%;
}
.heading {
  text-align: center;
  font-size: 3rem;
  color: black;
  padding: 1rem;
  padding-top: 8.5rem;
  width: 50rem;
  margin: 0 auto;
}
img {
  cursor: pointer;
}
.about {
  list-style-type: none;
  text-align: center;
  margin: 0;
  padding: 0;
}
.about li {
  display: inline-block;
}
.nav-bar3 {
  color: #1f1c1c;
  list-style: none;
  font-size: 10px;
  letter-spacing: 0.05em;
  font-family: "Montserrat", sans-serif, Arial, sans-serif;
  color: #ffffff;
  z-index: 1;
  text-decoration: underline;
}

li a {
  display: block;
  color: black;
  text-align: center;
  padding: 10px 12px;
  text-decoration: none;
  font-weight: 600;
}
.active {
  height: 100%;
  opacity: 1;
  visibility: visible;
  transform: translate3d(0, 0, 0);
  transition-delay: 0s, 0.2s;
  background: rgba(255, 255, 255, 0.11);
  border-top: 3px solid #01b3a7;
}
li a:hover {
  height: 100%;
  opacity: 1;
  visibility: visible;
  transform: translate3d(0, 0, 0);
  transition-delay: 0s, 0.2s;
  background: rgba(255, 255, 255, 0.11);
  border-top: 3px solid #01b3a7;
}
.about {
  cursor: pointer;
}
.about1 {
  color: #01b3a7;
}
.section6 {
  text-align: center;
  display: flex;
  justify-content: stretch;
}

#berry {
  width: 100%;
  display: inline-block;
  margin: 0;
}
#berry img {
  width: 75%;
  padding-top: 35px;
}
#right {
  margin: 0;
  display: inline-block;
  background-position: center;
  background-size: cover;
}

#right #txt {
  margin: 100px;
}

#right #txt h3 {
  font-size: 44px;
  font-weight: 600;
  margin: 0 0 8px;
}
#right #txt h5 {
  font-size: 14px;
  color: #8b8b99;
  line-height: 1.6;
  margin: 0;
}

#right #txt p {
  font-size: 16px;
  color: #8b8b99;
  line-height: 1.6;
  margin: 0;
}

.sub-btn {
  display: inline;
}
#sub-btn1 {
  background-color: #01b3a7;
  padding: 16px 42px;
  border-radius: 4px;
  cursor: pointer;
  color: white;
  border: 0;
  font-size: 10px;
  font-weight: 600;
  text-transform: uppercase;
  margin-top: 16px;
  display: inline;
  margin-right: 10px;
}
#sub-btn2 {
  background-color: #ffffff;
  padding: 16px 42px;
  border-radius: 4px;
  cursor: pointer;
  color: rgb(12, 12, 12);
  border-color: #151515;
  border: 1px solid black;
  font-size: 10px;
  font-weight: 600;
  text-transform: uppercase;
  margin-top: 16px;
  display: inline;
}
#sub-btn1:hover {
  color: #01b3a7;
  border: 1px solid #01b3a7;
  background-color: transparent;
}
#sub-btn2:hover {
  color: #01b3a7;
  border: 1px solid #01b3a7;
  background-color: transparent;
}

.features {
  min-height: 70vh;
  margin-top: -120px;
}

.features .box-container {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
  cursor: pointer;
}

.features .box-container .box {
  text-align: center;
  margin: 1rem;
  padding: 1rem;
  border: 0.2rem solid rgb(160, 160, 160);
  width: 17rem;
}

.features .box-container .box:hover {
  background: var(--gradient);
}

.features .box-container .box i {
  height: 4rem;
  width: 4rem;
  line-height: 4rem;
  text-align: center;
  border-radius: 50%;
  background: #01b3a7;
  color: #ffffff;
  font-size: 2rem;
  margin: 1rem 0;
}

.features .box-container .box h3 {
  color: black;
  font-size: 1.5rem;
}

.features .box-container .box p {
  color: black;
  font-size: 1.2rem;
  padding: 1rem 0.5rem;
}
.features .box-container .box h3:hover {
  cursor: pointer;
  font-size: 1.5rem;
  color: #01b3a7;
}
.section8 {
  margin-top: -70px;
}
.sec8 {
  background-color: #ffffff;
  display: flex;
  justify-content: space-between;
  padding: 40px;
  width: 60%;
  margin: -36px auto -72px auto;
}
.sec8 img {
  height: 250px;
  margin: 10px;
}
.sec8 h2 {
  margin: 10px;
  color: black;
  margin-left: 10px;
}
.sec8 p {
  color: #798897;
  padding-left: 10px;
}

@media screen and (max-width: 768px) {
  .section6 {
    flex-direction: column;
  }
  #right #txt {
    margin: 15px;
  }
  .heading {
    width: auto;
  }
  .sec8 {
    width: 90%;
    padding: 0;
    margin: 0 auto;
  }
  .nav-bar3 {
    display: flex;
    padding-left: 0;
    margin: auto;
    gap: 8px;
    justify-content: center;
  }
  #sub-btn2 {
    display: block;
  }
  .sub-btn {
    display: flex;
    justify-content: center;
  }
}
