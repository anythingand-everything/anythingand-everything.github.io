import React from 'react'

import Header from './header'
import './home.css'

const Home = (props) => {
  return (
    <div className="home-container">
      <Header></Header>
      <div className="home-hero">
        <div className="home-container1">
          <div className="home-card">
            <h1 className="home-text HeadingOne">Anything and Everything</h1>
            <span className="home-text1">
              <span className="Lead">
                Whether you&apos;re at home or at school, this is your stop for
                anything you need. From games to PowerPoints to tutorials,
                we&apos;ve got everything.
              </span>
              <br></br>
            </span>
          </div>
        </div>
      </div>
      <img
        alt="image"
        src="/playground_assets/curved6-1500h.jpg"
        className="home-image"
      />
      <section className="home-testimonials">
        <img
          alt="image"
          src="/playground_assets/waves-white.svg"
          className="home-image1"
        />
      </section>
    </div>
  )
}

export default Home
