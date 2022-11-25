import React from 'react'

import DangerousHTML from 'dangerous-html/react'

import Navbar from './navbar'
import Mark from './mark'
import Card from './card'
import Accordion from './accordion'
import Includes from './includes'
import Excludes from './excludes'
import Review from './review'
import Article from './article'
import FAQ from './f-a-q'

const Home = (props) => {
  return (
    <div
      style={{
        width: '100%',
        display: 'flex',
        overflow: 'auto',
        minHeight: '100vh',
        overflowX: 'hidden',
        alignItems: 'center',
        flexDirection: 'column',
        backgroundColor: '#0F0F0F',
      }}
    >
      <Navbar rootClassName="rootClassName"></Navbar>
      <section
        style={{
          width: '100%',
          height: '80vh',
          display: 'flex',
          alignItems: 'center',
          borderColor: '#51515A',
          paddingLeft: 'var(--dl-space-space-oneandhalfunits)',
          paddingRight: 'var(--dl-space-space-oneandhalfunits)',
          flexDirection: 'column',
          justifyContent: 'center',
          borderBottomWidth: '1px',
        }}
      >
        <div
          style={{
            width: '100%',
            display: 'flex',
            maxWidth: '1200px',
            alignItems: 'center',
            flexDirection: 'row',
            justifyContent: 'space-between',
          }}
        >
          <div
            style={{
              gap: 'var(--dl-space-space-fiveunits)',
              width: '100%',
              display: 'flex',
              maxWidth: '600px',
              alignItems: 'flex-start',
              flexDirection: 'column',
            }}
          >
            <main
              style={{
                gap: 'var(--dl-space-space-threeunits)',
                display: 'flex',
                alignItems: 'flex-start',
                flexDirection: 'column',
              }}
            >
              <header
                style={{
                  gap: 'var(--dl-space-space-unit)',
                  display: 'flex',
                  alignItems: 'center',
                  flexDirection: 'column',
                }}
              >
                <h1
                  style={{
                    color: 'rgb(255, 255, 255)',
                    fontSize: '64px',
                    fontStyle: 'normal',
                    fontFamily: 'Poppins',
                    fontWeight: '600',
                  }}
                >
                  The fastest way to make a doctor appointment
                </h1>
                <span
                  style={{
                    color: 'rgb(255, 255, 255)',
                    fontSize: '20px',
                    fontFamily: 'Poppins',
                    lineHeight: '30px',
                  }}
                >
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                  do eiusmod tempor incididunt.
                </span>
              </header>
              <div
                style={{
                  gap: 'var(--dl-space-space-unit)',
                  display: 'flex',
                  alignItems: 'center',
                  flexDirection: 'row',
                }}
              >
                <div
                  style={{
                    display: 'flex',
                    backgroundColor: '#80FF44',
                  }}
                >
                  <span
                    style={{
                      color: '#0C100C',
                      fontSize: '16px',
                      fontStyle: 'normal',
                      fontFamily: 'Poppins',
                      fontWeight: '500',
                      lineHeight: '24px',
                    }}
                  >
                    Get started
                  </span>
                </div>
                <div
                  style={{
                    backgroundColor: '#2A2A2A',
                  }}
                >
                  <span
                    style={{
                      color: '#ffffff',
                      fontSize: '16px',
                      fontStyle: 'normal',
                      fontFamily: 'Poppins',
                      fontWeight: '500',
                      lineHeight: '24px',
                    }}
                  >
                    View features
                  </span>
                </div>
              </div>
            </main>
            <div
              style={{
                gap: 'var(--dl-space-space-unit)',
                display: 'flex',
                alignItems: 'center',
                flexDirection: 'row',
              }}
            >
              <div
                style={{
                  width: '115px',
                  height: 'var(--dl-size-size-small)',
                  display: 'flex',
                  position: 'relative',
                  alignItems: 'center',
                  flexDirection: 'row',
                }}
              >
                <img
                  alt="image"
                  src="https://images.unsplash.com/photo-1552234994-66ba234fd567?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDN8fHBvdHJhaXR8ZW58MHx8fHwxNjY3MjQ0ODcx&amp;ixlib=rb-4.0.3&amp;w=200"
                  style={{
                    left: '0px',
                    position: 'absolute',
                  }}
                />
                <img
                  alt="image"
                  src="https://images.unsplash.com/photo-1610276198568-eb6d0ff53e48?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDF8fHBvdHJhaXR8ZW58MHx8fHwxNjY3MjQ0ODcx&amp;ixlib=rb-4.0.3&amp;w=200"
                  style={{
                    left: 'var(--dl-space-space-twounits)',
                    position: 'absolute',
                    objectFit: 'cover',
                  }}
                />
                <img
                  alt="image"
                  src="https://images.unsplash.com/photo-1618151313441-bc79b11e5090?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDEzfHxwb3RyYWl0fGVufDB8fHx8MTY2NzI0NDg3MQ&amp;ixlib=rb-4.0.3&amp;w=200"
                  style={{
                    left: 'var(--dl-space-space-fourunits)',
                    position: 'absolute',
                    objectFit: 'cover',
                  }}
                />
              </div>
              <label
                style={{
                  color: 'rgb(255, 255, 255)',
                  fontFamily: 'Poppins',
                  lineHeight: '24px',
                }}
              >
                Loved by 10,000+ people like you.
              </label>
            </div>
          </div>
          <div
            style={{
              top: '150px',
              right: '0px',
              width: '650px',
              border: '2px dashed rgba(120, 120, 120, 0.4)',
              height: '900px',
              margin: 'auto',
              display: 'flex',
              position: 'absolute',
              alignItems: 'center',
              flexDirection: 'row',
              justifyContent: 'space-between',
            }}
          ></div>
          <div
            style={{
              display: 'none',
            }}
          >
            <img alt="image" src="/playground_assets/heroimage-1500h.png" />
          </div>
        </div>
      </section>
      <section
        style={{
          flex: '1',
          width: '100%',
          display: 'flex',
          alignItems: 'center',
          paddingTop: '120px',
          paddingLeft: 'var(--dl-space-space-oneandhalfunits)',
          paddingRight: 'var(--dl-space-space-oneandhalfunits)',
          flexDirection: 'column',
          paddingBottom: '120px',
          justifyContent: 'center',
        }}
      >
        <h2
          style={{
            color: '#ffffff',
            fontSize: '40px',
            fontStyle: 'normal',
            fontFamily: 'Poppins',
            fontWeight: '600',
          }}
        >
          Our doctors and therapists are here, 24/7.
        </h2>
        <div
          style={{
            width: '100%',
            display: 'flex',
            maxWidth: '1200px',
            marginTop: 'var(--dl-space-space-fiveunits)',
            alignItems: 'center',
            userSelect: 'none',
            borderColor: '#5A5A5A',
            marginBottom: '120px',
            flexDirection: 'row',
            justifyContent: 'center',
            borderBottomWidth: '1px',
          }}
        >
          <header>
            <h3
              style={{
                color: 'rgb(255, 255, 255)',
                fontSize: '24px',
                fontStyle: 'normal',
                fontFamily: 'Poppins',
                fontWeight: '600',
              }}
            >
              Urgent Care
            </h3>
            <p
              style={{
                color: 'rgb(121, 124, 128)',
                fontFamily: 'Poppins',
              }}
            >
              Doloremque laudantium
            </p>
          </header>
          <header>
            <h3
              style={{
                color: 'rgb(255, 255, 255)',
                fontSize: '24px',
                fontStyle: 'normal',
                fontFamily: 'Poppins',
                fontWeight: '600',
              }}
            >
              Chronic Care
            </h3>
            <p
              style={{
                color: 'rgb(121, 124, 128)',
                fontFamily: 'Poppins',
              }}
            >
              Doloremque laudantium
            </p>
          </header>
          <header>
            <h3
              style={{
                color: 'rgb(255, 255, 255)',
                fontSize: '24px',
                fontStyle: 'normal',
                fontFamily: 'Poppins',
                fontWeight: '600',
              }}
            >
              Mental Health
            </h3>
            <p
              style={{
                color: 'rgb(121, 124, 128)',
                fontFamily: 'Poppins',
              }}
            >
              Doloremque laudantium
            </p>
          </header>
        </div>
        <div
          style={{
            gap: '140px',
            width: '100%',
            display: 'flex',
            maxWidth: '1200px',
            alignItems: 'center',
            flexDirection: 'row',
            justifyContent: 'center',
          }}
        >
          <div
            style={{
              gap: 'var(--dl-space-space-threeunits)',
              flex: '1',
              display: 'flex',
              maxWidth: '520px',
              alignItems: 'flex-start',
              flexDirection: 'column',
              justifyContent: 'center',
            }}
          >
            <main
              style={{
                gap: 'var(--dl-space-space-oneandhalfunits)',
                display: 'flex',
                alignItems: 'center',
                flexDirection: 'column',
                justifyContent: 'center',
              }}
            >
              <h2
                style={{
                  color: 'rgb(255, 255, 255)',
                  fontSize: '32px',
                  fontStyle: 'normal',
                  fontFamily: 'Poppins',
                  fontWeight: '500',
                }}
              >
                Accessing this Medicare benefit is easy
              </h2>
              <p
                style={{
                  color: '#CCCCCC',
                  fontFamily: 'Poppins',
                  lineHeight: '28px',
                }}
              >
                <span>
                  Sed ut perspiciatis unde omnis iste natus error sit voluptatem
                  accusantium doloremque laudantium, totam rem aperiam, eaque
                  ipsa quae ab illo inventore veritatis et quasi architecto
                  beatae.
                </span>
                <br></br>
                <br></br>
                <span>
                  Doloremque laudantium, totam rem aperiam, eaque ipsa quae ab
                  illo inventore veritatis et quasi architecto beatae.
                </span>
                <br></br>
              </p>
            </main>
            <div
              style={{
                gap: 'var(--dl-space-space-oneandhalfunits)',
                cursor: 'pointer',
                display: 'flex',
                alignItems: 'center',
                transition: '0.3s',
                borderColor: '#80FF44',
                flexDirection: 'column',
                paddingBottom: 'var(--dl-space-space-halfunit)',
                justifyContent: 'center',
                borderBottomWidth: '1px',
              }}
            >
              <p
                style={{
                  color: '#80FF44',
                  fontStyle: 'normal',
                  fontWeight: '500',
                  lineHeight: '24px',
                }}
              >
                Explore more -&gt;
              </p>
            </div>
          </div>
          <div
            style={{
              flex: '1',
              display: 'flex',
              alignItems: 'center',
              flexDirection: 'row',
              justifyContent: 'flex-end',
            }}
          >
            <img
              alt="image"
              src="/playground_assets/group%201490-1200w.png"
              style={{
                objectFit: 'cover',
              }}
            />
          </div>
        </div>
      </section>
      <section
        style={{
          gap: 'var(--dl-space-space-sixunits)',
          flex: '1',
          width: '100%',
          display: 'flex',
          alignItems: 'center',
          paddingTop: 'var(--dl-space-space-twounits)',
          paddingLeft: 'var(--dl-space-space-oneandhalfunits)',
          paddingRight: 'var(--dl-space-space-oneandhalfunits)',
          flexDirection: 'column',
          paddingBottom: '120px',
          justifyContent: 'center',
        }}
      >
        <header
          style={{
            gap: 'var(--dl-space-space-unit)',
            width: '100%',
            display: 'flex',
            maxWidth: '900px',
            alignItems: 'center',
            flexDirection: 'column',
            justifyContent: 'center',
          }}
        >
          <h2
            style={{
              color: 'rgb(255, 255, 255)',
              fontSize: '40px',
              fontStyle: 'normal',
              fontFamily: 'Poppins',
              fontWeight: '600',
            }}
          >
            Why do you need a mobile medical app?
          </h2>
          <span
            style={{
              color: '#C2C6CC',
              width: '100%',
              maxWidth: '600px',
              textAlign: 'center',
              fontFamily: 'Poppins',
              lineHeight: '28px',
            }}
          >
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt.
          </span>
        </header>
        <section
          style={{
            width: '100%',
            display: 'flex',
            maxWidth: '1200px',
            alignItems: 'center',
            flexDirection: 'row',
            justifyContent: 'center',
          }}
        >
          <div
            style={{
              flex: '1',
              display: 'flex',
              alignItems: 'center',
              flexDirection: 'row',
              justifyContent: 'center',
            }}
          >
            <img
              alt="image"
              src="/playground_assets/group%201428-1200w.png"
              style={{
                objectFit: 'cover',
              }}
            />
          </div>
          <div
            style={{
              gap: 'var(--dl-space-space-threeunits)',
              flex: '1',
              display: 'flex',
              maxWidth: '600px',
              alignItems: 'flex-start',
              flexDirection: 'column',
              justifyContent: 'center',
            }}
          >
            <div
              style={{
                gap: 'var(--dl-space-space-oneandhalfunits)',
                display: 'flex',
                alignItems: 'flex-start',
                flexDirection: 'column',
                justifyContent: 'center',
              }}
            >
              <div
                style={{
                  display: 'flex',
                  alignItems: 'center',
                  flexDirection: 'column',
                  justifyContent: 'center',
                }}
              >
                <span>Tempor incididunt</span>
              </div>
              <div
                style={{
                  gap: 'var(--dl-space-space-unit)',
                  width: '100%',
                  display: 'flex',
                  maxWidth: '600px',
                  alignItems: 'flex-start',
                  flexDirection: 'column',
                  justifyContent: 'center',
                }}
              >
                <h2>We provide compassionate care from start to finish.</h2>
                <p>
                  Sed ut perspiciatis unde omnis iste natus error sit voluptatem
                  accusantium doloremque laudantium, totam rem aperiam, eaque
                  ipsa quae ab illo inventore veritatis et quasi architecto
                  beatae.
                </p>
              </div>
            </div>
            <div
              style={{
                display: 'flex',
                backgroundColor: '#80FF44',
              }}
            >
              <span
                style={{
                  color: '#0C100C',
                  fontSize: '16px',
                  fontStyle: 'normal',
                  fontFamily: 'Poppins',
                  fontWeight: '500',
                  lineHeight: '24px',
                }}
              >
                Get started
              </span>
            </div>
          </div>
        </section>
        <section
          style={{
            width: '100%',
            display: 'flex',
            maxWidth: '1200px',
            alignItems: 'center',
            flexDirection: 'row-reverse',
            justifyContent: 'center',
          }}
        >
          <div
            style={{
              flex: '1',
              display: 'flex',
              alignItems: 'center',
              flexDirection: 'row',
              justifyContent: 'center',
            }}
          >
            <img
              alt="image"
              src="/playground_assets/group%201449-1200w.png"
              style={{
                objectFit: 'cover',
              }}
            />
          </div>
          <div
            style={{
              gap: 'var(--dl-space-space-threeunits)',
              flex: '1',
              display: 'flex',
              maxWidth: '600px',
              alignItems: 'flex-start',
              flexDirection: 'column',
              justifyContent: 'center',
            }}
          >
            <main
              style={{
                gap: 'var(--dl-space-space-oneandhalfunits)',
                display: 'flex',
                alignItems: 'flex-start',
                flexDirection: 'column',
                justifyContent: 'center',
              }}
            >
              <header
                style={{
                  display: 'flex',
                  alignItems: 'center',
                  flexDirection: 'column',
                  justifyContent: 'center',
                }}
              >
                <span
                  style={{
                    color: 'rgb(198, 255, 75)',
                  }}
                >
                  Tempor incididunt
                </span>
              </header>
              <main
                style={{
                  gap: 'var(--dl-space-space-twounits)',
                  width: '100%',
                  display: 'flex',
                  maxWidth: '600px',
                  alignItems: 'flex-start',
                  flexDirection: 'column',
                  justifyContent: 'center',
                }}
              >
                <header
                  style={{
                    gap: 'var(--dl-space-space-unit)',
                    display: 'flex',
                    alignItems: 'flex-start',
                    flexDirection: 'column',
                    justifyContent: 'center',
                  }}
                >
                  <h2>Great care, wherever you are</h2>
                  <p>
                    Sed ut perspiciatis unde omnis iste natus error sit
                    voluptatem accusantium doloremque laudantium.
                  </p>
                </header>
                <div
                  style={{
                    gap: 'var(--dl-space-space-unit)',
                    display: 'flex',
                    alignItems: 'flex-start',
                    flexDirection: 'column',
                    justifyContent: 'flex-start',
                  }}
                >
                  <Mark></Mark>
                  <Mark Label="Quis nostrud exercitation ullamco"></Mark>
                  <Mark Label="Reprehenderit qui in ea voluptate velit"></Mark>
                </div>
              </main>
            </main>
            <div
              style={{
                display: 'flex',
                backgroundColor: '#80FF44',
              }}
            >
              <span
                style={{
                  color: '#0C100C',
                  fontSize: '16px',
                  fontStyle: 'normal',
                  fontFamily: 'Poppins',
                  fontWeight: '500',
                  lineHeight: '24px',
                }}
              >
                Get started
              </span>
            </div>
          </div>
        </section>
      </section>
      <section
        style={{
          gap: 'var(--dl-space-space-fiveunits)',
          flex: '1',
          width: '100%',
          display: 'flex',
          alignItems: 'center',
          paddingTop: '120px',
          borderColor: '#51515A',
          paddingLeft: 'var(--dl-space-space-oneandhalfunits)',
          paddingRight: 'var(--dl-space-space-oneandhalfunits)',
          flexDirection: 'column',
          paddingBottom: '120px',
          borderTopWidth: '1px',
          justifyContent: 'center',
        }}
      >
        <header
          style={{
            width: '100%',
            display: 'flex',
            maxWidth: '1200px',
            alignItems: 'center',
            flexDirection: 'row',
            justifyContent: 'space-between',
          }}
        >
          <header
            style={{
              gap: 'var(--dl-space-space-oneandhalfunits)',
              width: '100%',
              display: 'flex',
              maxWidth: '600px',
              alignItems: 'flex-start',
              flexDirection: 'column',
              justifyContent: 'center',
            }}
          >
            <span>Tempor incididunt</span>
            <h2>
              <span>Meet our network</span>
              <br></br>
              <span>of licensed providers</span>
            </h2>
          </header>
          <div
            style={{
              gap: 'var(--dl-space-space-unit)',
              display: 'flex',
              alignItems: 'center',
              flexDirection: 'column',
              justifyContent: 'center',
            }}
          >
            <p
              style={{
                width: '100%',
                maxWidth: '480px',
              }}
            >
              Sed ut perspiciatis unde omnis iste natus error sit voluptatem
              accusantium doloremque laudantium, totam rem aperiam.
            </p>
          </div>
        </header>
        <main
          style={{
            gap: 'var(--dl-space-space-threeunits)',
            width: '100%',
            display: 'flex',
            maxWidth: '1200px',
            alignItems: 'center',
            flexDirection: 'row',
            justifyContent: 'center',
          }}
        >
          <Card rootClassName="rootClassName"></Card>
          <Card
            Icon="/playground_assets/group%201314-200h.png"
            rootClassName="rootClassName1"
          ></Card>
          <Card
            Icon="/playground_assets/group%201317-200h.png"
            rootClassName="rootClassName2"
          ></Card>
        </main>
      </section>
      <section
        style={{
          gap: 'var(--dl-space-space-fiveunits)',
          flex: '1',
          width: '100%',
          display: 'flex',
          alignItems: 'center',
          paddingTop: 'var(--dl-space-space-fourunits)',
          paddingLeft: 'var(--dl-space-space-oneandhalfunits)',
          paddingRight: 'var(--dl-space-space-oneandhalfunits)',
          flexDirection: 'column',
          justifyContent: 'center',
        }}
      >
        <div
          style={{
            width: '100%',
            display: 'flex',
            maxWidth: '1200px',
            alignItems: 'center',
            flexDirection: 'row-reverse',
            justifyContent: 'center',
          }}
        >
          <div
            style={{
              flex: '1',
              display: 'flex',
              alignItems: 'center',
              flexDirection: 'row',
              justifyContent: 'center',
            }}
          >
            <img
              alt="image"
              src="/playground_assets/iphone%2014%20pro%20max-1200w.png"
              style={{
                objectFit: 'cover',
              }}
            />
          </div>
          <div
            style={{
              gap: 'var(--dl-space-space-oneandhalfunits)',
              flex: '1',
              display: 'flex',
              maxWidth: '600px',
              alignItems: 'flex-start',
              flexDirection: 'column',
              justifyContent: 'center',
            }}
          >
            <div
              style={{
                display: 'flex',
                alignItems: 'center',
                flexDirection: 'column',
                justifyContent: 'center',
              }}
            >
              <span>Tempor incididunt</span>
            </div>
            <div
              style={{
                gap: 'var(--dl-space-space-oneandhalfunits)',
                width: '100%',
                display: 'flex',
                maxWidth: '600px',
                alignItems: 'flex-start',
                flexDirection: 'column',
                justifyContent: 'center',
              }}
            >
              <div
                style={{
                  gap: 'var(--dl-space-space-unit)',
                  display: 'flex',
                  alignItems: 'flex-start',
                  flexDirection: 'column',
                  justifyContent: 'center',
                }}
              >
                <h2>Tips to get care, answers and advice faster</h2>
              </div>
              <Accordion rootClassName="rootClassName"></Accordion>
            </div>
          </div>
        </div>
      </section>
      <section
        style={{
          gap: 'var(--dl-space-space-fiveunits)',
          flex: '1',
          width: '100%',
          display: 'flex',
          position: 'relative',
          alignItems: 'center',
          paddingLeft: 'var(--dl-space-space-oneandhalfunits)',
          paddingRight: 'var(--dl-space-space-oneandhalfunits)',
          flexDirection: 'column',
          paddingBottom: '120px',
          justifyContent: 'center',
        }}
      >
        <div
          style={{
            top: '20px',
            left: '0px',
            width: '120px',
            height: '120px',
            display: 'flex',
            position: 'absolute',
            transform: 'rotateX(240deg) rotateY(25deg) rotateZ(-110deg)',
            alignItems: 'center',
            flexDirection: 'column',
            justifyContent: 'center',
            transformStyle: 'preserve-3d',
          }}
        >
          <div
            style={{
              transform: 'translateZ(-120px)',
              backgroundImage:
                'linear-gradient(270deg, rgb(253, 253, 253) 0.00%,rgb(178, 178, 178) 100.00%)',
            }}
          ></div>
          <div
            style={{
              transform: 'rotateX(90deg)',
              background: 'grey',
              backgroundImage:
                'linear-gradient(90deg, rgb(247, 247, 247) 0.00%,rgb(203, 203, 203) 100.00%)',
              transformOrigin: 'bottom',
            }}
          ></div>
          <div
            style={{
              width: '120px',
              transform: 'translateZ(-120px) rotateY(90deg)',
              backgroundImage:
                'linear-gradient(90deg, rgb(247, 247, 247) 0.00%,rgb(203, 203, 203) 100.00%)',
              transformOrigin: 'right',
            }}
          ></div>
        </div>
        <main
          style={{
            width: '100%',
            zIndex: '50',
            display: 'flex',
            padding: 'var(--dl-space-space-fiveunits)',
            maxWidth: '1200px',
            alignItems: 'center',
            borderRadius: '20px',
            justifyContent: 'space-between',
            backgroundColor: '#292929',
          }}
        >
          <div
            style={{
              gap: 'var(--dl-space-space-unit)',
              width: '100%',
              display: 'flex',
              maxWidth: '600px',
              alignItems: 'flex-start',
              flexDirection: 'column',
              justifyContent: 'flex-start',
            }}
          >
            <h2>Planical makes online doctor visits easier</h2>
            <p
              style={{
                fontSize: '20px',
                lineHeight: '30px',
              }}
            >
              Lorem ipsum dolor sit amet!
            </p>
          </div>
          <div
            style={{
              gap: 'var(--dl-space-space-unit)',
              display: 'flex',
              alignItems: 'center',
              justifyContent: 'center',
            }}
          >
            <div
              style={{
                display: 'flex',
                backgroundColor: '#80FF44',
              }}
            >
              <span
                style={{
                  color: '#0C100C',
                  fontSize: '16px',
                  fontStyle: 'normal',
                  fontFamily: 'Poppins',
                  fontWeight: '500',
                  lineHeight: '24px',
                  whiteSpace: 'nowrap',
                }}
              >
                Get started
              </span>
            </div>
            <div
              style={{
                display: 'flex',
                backgroundColor: '#ffffff',
              }}
            >
              <span
                style={{
                  color: 'rgb(12, 16, 12)',
                  fontSize: '16px',
                  fontStyle: 'normal',
                  fontFamily: 'Poppins',
                  fontWeight: '500',
                  lineHeight: '24px',
                  whiteSpace: 'nowrap',
                }}
              >
                Book a demo
              </span>
            </div>
          </div>
        </main>
      </section>
      <section
        style={{
          gap: 'var(--dl-space-space-threeunits)',
          flex: '1',
          width: '100%',
          display: 'flex',
          position: 'relative',
          alignItems: 'center',
          paddingLeft: 'var(--dl-space-space-oneandhalfunits)',
          paddingRight: 'var(--dl-space-space-oneandhalfunits)',
          flexDirection: 'column',
          paddingBottom: '120px',
          justifyContent: 'center',
        }}
      >
        <div
          style={{
            right: '-150px',
            width: '210px',
            bottom: '-80px',
            height: '210px',
            margin: 'auto',
            display: 'flex',
            position: 'absolute',
            transform: 'rotateX(240deg) rotateY(50deg) rotateZ(-110deg)',
            alignItems: 'center',
            flexDirection: 'column',
            justifyContent: 'center',
            transformStyle: 'preserve-3d',
          }}
        >
          <div
            style={{
              transform: 'translateZ(-210px)',
              backgroundImage:
                'linear-gradient(270deg, rgb(253, 253, 253) 0.00%,rgb(178, 178, 178) 100.00%)',
            }}
          ></div>
          <div
            style={{
              transform: 'rotateX(90deg)',
              background: 'grey',
              backgroundImage:
                'linear-gradient(90deg, rgb(247, 247, 247) 0.00%,rgb(203, 203, 203) 100.00%)',
              transformOrigin: 'bottom',
            }}
          ></div>
          <div
            style={{
              width: '210px',
              transform: 'translateZ(-210px) rotateY(90deg)',
              backgroundImage:
                'linear-gradient(90deg, rgb(247, 247, 247) 0.00%,rgb(203, 203, 203) 100.00%)',
              transformOrigin: 'right',
            }}
          ></div>
        </div>
        <main
          style={{
            gap: 'var(--dl-space-space-threeunits)',
            width: '100%',
            zIndex: '50',
            display: 'flex',
            maxWidth: '1200px',
            alignItems: 'center',
            borderRadius: '20px',
            flexDirection: 'column',
            justifyContent: 'center',
          }}
        >
          <header
            style={{
              gap: 'var(--dl-space-space-unit)',
              width: '100%',
              display: 'flex',
              maxWidth: '900px',
              alignItems: 'center',
              flexDirection: 'column',
              justifyContent: 'center',
            }}
          >
            <header
              style={{
                gap: 'var(--dl-space-space-oneandhalfunits)',
                width: '100%',
                display: 'flex',
                maxWidth: '600px',
                alignItems: 'center',
                flexDirection: 'column',
                justifyContent: 'center',
              }}
            >
              <span>Pricing</span>
              <h2>Start small, think big</h2>
            </header>
            <div
              style={{
                gap: 'var(--dl-space-space-unit)',
                display: 'flex',
                alignItems: 'center',
                flexDirection: 'column',
                justifyContent: 'center',
              }}
            >
              <p
                style={{
                  width: '100%',
                  fontSize: '18px',
                  maxWidth: '600px',
                  textAlign: 'center',
                  lineHeight: '32px',
                }}
              >
                Sed ut perspiciatis unde omnis iste natus error sit voluptatem
                accusantium doloremque laudantium, totam rem aperiam.
              </p>
            </div>
          </header>
          <div
            style={{
              gap: 'var(--dl-space-space-fiveunits)',
              width: '100%',
              display: 'flex',
              alignItems: 'center',
              flexDirection: 'column',
              justifyContent: 'center',
            }}
          >
            <div
              style={{
                gap: 'var(--dl-space-space-unit)',
                display: 'flex',
                padding: 'var(--dl-space-space-halfunit)',
                alignItems: 'center',
                borderRadius: '50px',
                flexDirection: 'row',
                justifyContent: 'center',
                backgroundColor: '#292929',
              }}
            >
              <div>
                <label
                  style={{
                    color: '#ffffff',
                    fontStyle: 'normal',
                    fontWeight: '500',
                    lineHeight: '24px',
                  }}
                >
                  Monthly
                </label>
              </div>
              <div
                style={{
                  paddingTop: 'var(--dl-space-space-unit)',
                  backgroundColor: '#80FF44',
                }}
              >
                <label
                  style={{
                    color: 'rgb(0, 0, 0)',
                    fontStyle: 'normal',
                    fontWeight: '500',
                    lineHeight: '24px',
                  }}
                >
                  Yearly
                </label>
              </div>
            </div>
            <main
              style={{
                gap: 'var(--dl-space-space-threeunits)',
                width: '100%',
                zIndex: '50',
                display: 'flex',
                padding: 'var(--dl-space-space-halfunit)',
                maxWidth: '1200px',
                alignItems: 'center',
                borderRadius: '50px',
                flexDirection: 'row',
                justifyContent: 'center',
              }}
            >
              <div
                style={{
                  gap: 'var(--dl-space-space-threeunits)',
                  flex: '1',
                  display: 'flex',
                  alignItems: 'flex-start',
                  paddingTop: 'var(--dl-space-space-fiveunits)',
                  paddingLeft: 'var(--dl-space-space-twounits)',
                  borderRadius: '20px',
                  paddingRight: 'var(--dl-space-space-twounits)',
                  flexDirection: 'column',
                  paddingBottom: 'var(--dl-space-space-fiveunits)',
                  justifyContent: 'flex-start',
                  backgroundColor: '#292929',
                }}
              >
                <div
                  style={{
                    gap: 'var(--dl-space-space-twounits)',
                    display: 'flex',
                    alignItems: 'flex-start',
                    flexDirection: 'column',
                    justifyContent: 'flex-start',
                  }}
                >
                  <div
                    style={{
                      gap: 'var(--dl-space-space-oneandhalfunits)',
                      display: 'flex',
                      alignItems: 'flex-start',
                      flexDirection: 'column',
                      justifyContent: 'flex-start',
                    }}
                  >
                    <label
                      style={{
                        color: 'rgb(255, 255, 255)',
                        fontSize: '24px',
                        fontFamily: 'Poppins',
                        lineHeight: '36px',
                      }}
                    >
                      Basic
                    </label>
                    <div
                      style={{
                        gap: 'var(--dl-space-space-halfunit)',
                        display: 'flex',
                        alignItems: 'center',
                        flexDirection: 'row',
                        justifyContent: 'center',
                      }}
                    >
                      <h1
                        style={{
                          color: '#ffffff',
                          fontSize: '40px',
                          fontStyle: 'normal',
                          fontFamily: 'Poppins',
                          fontWeight: '600',
                        }}
                      >
                        $9
                      </h1>
                      <span
                        style={{
                          color: '#B3B3B3',
                          fontSize: '20px',
                          fontFamily: 'Poppins',
                          lineHeight: '40px',
                        }}
                      >
                        /mo
                      </span>
                    </div>
                  </div>
                  <p
                    style={{
                      color: 'rgba(255, 255, 255, 0.8)',
                      fontFamily: 'Poppins',
                      lineHeight: '22px',
                    }}
                  >
                    Good for sed quia consequuntur magni dolores eos qui
                    ratione.
                  </p>
                </div>
                <div
                  style={{
                    gap: 'var(--dl-space-space-twounits)',
                    width: '100%',
                    display: 'flex',
                    alignItems: 'flex-start',
                    flexDirection: 'column',
                    justifyContent: 'flex-start',
                  }}
                >
                  <div
                    style={{
                      width: '100%',
                      display: 'flex',
                      backgroundColor: '#80FF44',
                    }}
                  >
                    <span
                      style={{
                        color: 'rgb(12, 16, 12)',
                        fontSize: '16px',
                        fontStyle: 'normal',
                        fontFamily: 'Poppins',
                        fontWeight: '500',
                        lineHeight: '24px',
                      }}
                    >
                      <span>Start Basic</span>
                      <br></br>
                    </span>
                  </div>
                  <div
                    style={{
                      gap: 'var(--dl-space-space-unit)',
                      display: 'flex',
                      alignItems: 'flex-start',
                      flexDirection: 'column',
                      justifyContent: 'flex-start',
                    }}
                  >
                    <span
                      style={{
                        color: 'rgb(255, 255, 255)',
                        fontStyle: 'normal',
                        fontFamily: 'Poppins',
                        fontWeight: '500',
                        lineHeight: '28px',
                      }}
                    >
                      You will get
                    </span>
                    <div
                      style={{
                        gap: 'var(--dl-space-space-unit)',
                        display: 'flex',
                        alignItems: 'flex-start',
                        flexDirection: 'column',
                        justifyContent: 'flex-start',
                      }}
                    >
                      <Includes rootClassName="rootClassName"></Includes>
                      <Includes rootClassName="rootClassName"></Includes>
                      <Includes rootClassName="rootClassName"></Includes>
                      <Includes rootClassName="rootClassName"></Includes>
                      <Excludes rootClassName="rootClassName"></Excludes>
                      <Excludes rootClassName="rootClassName"></Excludes>
                      <Excludes rootClassName="rootClassName"></Excludes>
                      <Excludes rootClassName="rootClassName"></Excludes>
                      <Excludes rootClassName="rootClassName"></Excludes>
                      <Excludes rootClassName="rootClassName"></Excludes>
                    </div>
                  </div>
                </div>
              </div>
              <div
                style={{
                  gap: 'var(--dl-space-space-threeunits)',
                  flex: '1',
                  display: 'flex',
                  alignItems: 'flex-start',
                  paddingTop: 'var(--dl-space-space-fiveunits)',
                  paddingLeft: 'var(--dl-space-space-twounits)',
                  borderRadius: '20px',
                  paddingRight: 'var(--dl-space-space-twounits)',
                  flexDirection: 'column',
                  paddingBottom: 'var(--dl-space-space-fiveunits)',
                  justifyContent: 'flex-start',
                  backgroundColor: '#292929',
                }}
              >
                <div
                  style={{
                    gap: 'var(--dl-space-space-twounits)',
                    display: 'flex',
                    alignItems: 'flex-start',
                    flexDirection: 'column',
                    justifyContent: 'flex-start',
                  }}
                >
                  <div
                    style={{
                      gap: 'var(--dl-space-space-oneandhalfunits)',
                      display: 'flex',
                      alignItems: 'flex-start',
                      flexDirection: 'column',
                      justifyContent: 'flex-start',
                    }}
                  >
                    <label
                      style={{
                        color: 'rgb(255, 255, 255)',
                        fontSize: '24px',
                        fontFamily: 'Poppins',
                        lineHeight: '36px',
                      }}
                    >
                      Professional
                    </label>
                    <div
                      style={{
                        gap: 'var(--dl-space-space-halfunit)',
                        display: 'flex',
                        alignItems: 'center',
                        flexDirection: 'row',
                        justifyContent: 'center',
                      }}
                    >
                      <h1
                        style={{
                          color: 'rgb(255, 255, 255)',
                          fontSize: '40px',
                          fontStyle: 'normal',
                          fontFamily: 'Poppins',
                          fontWeight: '600',
                        }}
                      >
                        $15
                      </h1>
                      <span
                        style={{
                          color: '#B3B3B3',
                          fontSize: '20px',
                          fontFamily: 'Poppins',
                          lineHeight: '40px',
                        }}
                      >
                        /mo
                      </span>
                    </div>
                  </div>
                  <p
                    style={{
                      color: 'rgba(255, 255, 255, 0.8)',
                      fontFamily: 'Poppins',
                      lineHeight: '22px',
                    }}
                  >
                    Good for sed quia consequuntur magni dolores eos qui
                    ratione.
                  </p>
                </div>
                <div
                  style={{
                    gap: 'var(--dl-space-space-twounits)',
                    width: '100%',
                    display: 'flex',
                    alignItems: 'flex-start',
                    flexDirection: 'column',
                    justifyContent: 'flex-start',
                  }}
                >
                  <div
                    style={{
                      width: '100%',
                      display: 'flex',
                      backgroundColor: '#80FF44',
                    }}
                  >
                    <span
                      style={{
                        color: 'rgb(12, 16, 12)',
                        fontSize: '16px',
                        fontStyle: 'normal',
                        fontFamily: 'Poppins',
                        fontWeight: '500',
                        lineHeight: '24px',
                      }}
                    >
                      <span>Start Professional</span>
                      <br></br>
                    </span>
                  </div>
                  <div
                    style={{
                      gap: 'var(--dl-space-space-unit)',
                      display: 'flex',
                      alignItems: 'flex-start',
                      flexDirection: 'column',
                      justifyContent: 'flex-start',
                    }}
                  >
                    <span
                      style={{
                        color: 'rgb(255, 255, 255)',
                        fontStyle: 'normal',
                        fontFamily: 'Poppins',
                        fontWeight: '500',
                        lineHeight: '28px',
                      }}
                    >
                      You will get
                    </span>
                    <div
                      style={{
                        gap: 'var(--dl-space-space-unit)',
                        display: 'flex',
                        alignItems: 'flex-start',
                        flexDirection: 'column',
                        justifyContent: 'flex-start',
                      }}
                    >
                      <Includes rootClassName="rootClassName"></Includes>
                      <Includes rootClassName="rootClassName"></Includes>
                      <Includes rootClassName="rootClassName"></Includes>
                      <Includes rootClassName="rootClassName"></Includes>
                      <Includes rootClassName="rootClassName"></Includes>
                      <Includes rootClassName="rootClassName"></Includes>
                      <Includes rootClassName="rootClassName"></Includes>
                      <Excludes rootClassName="rootClassName"></Excludes>
                      <Excludes rootClassName="rootClassName"></Excludes>
                      <Excludes rootClassName="rootClassName"></Excludes>
                    </div>
                  </div>
                </div>
              </div>
              <div
                style={{
                  gap: 'var(--dl-space-space-threeunits)',
                  flex: '1',
                  display: 'flex',
                  alignItems: 'flex-start',
                  paddingTop: 'var(--dl-space-space-fiveunits)',
                  paddingLeft: 'var(--dl-space-space-twounits)',
                  borderRadius: '20px',
                  paddingRight: 'var(--dl-space-space-twounits)',
                  flexDirection: 'column',
                  paddingBottom: 'var(--dl-space-space-fiveunits)',
                  justifyContent: 'flex-start',
                  backgroundColor: '#292929',
                }}
              >
                <div
                  style={{
                    gap: 'var(--dl-space-space-twounits)',
                    display: 'flex',
                    alignItems: 'flex-start',
                    flexDirection: 'column',
                    justifyContent: 'flex-start',
                  }}
                >
                  <div
                    style={{
                      gap: 'var(--dl-space-space-oneandhalfunits)',
                      display: 'flex',
                      alignItems: 'flex-start',
                      flexDirection: 'column',
                      justifyContent: 'flex-start',
                    }}
                  >
                    <label
                      style={{
                        color: 'rgb(255, 255, 255)',
                        fontSize: '24px',
                        fontFamily: 'Poppins',
                        lineHeight: '36px',
                      }}
                    >
                      Enterprise
                    </label>
                    <div
                      style={{
                        gap: 'var(--dl-space-space-halfunit)',
                        display: 'flex',
                        alignItems: 'center',
                        flexDirection: 'row',
                        justifyContent: 'center',
                      }}
                    >
                      <span
                        style={{
                          color: 'rgb(255, 255, 255)',
                          fontSize: '40px',
                          fontStyle: 'normal',
                          fontFamily: 'Poppins',
                          fontWeight: '600',
                        }}
                      >
                        $99
                      </span>
                      <span
                        style={{
                          color: '#B3B3B3',
                          fontSize: '20px',
                          fontFamily: 'Poppins',
                          lineHeight: '40px',
                        }}
                      >
                        /mo
                      </span>
                    </div>
                  </div>
                  <p
                    style={{
                      color: 'rgba(255, 255, 255, 0.8)',
                      fontFamily: 'Poppins',
                      lineHeight: '22px',
                    }}
                  >
                    Good for sed quia consequuntur magni dolores eos qui
                    ratione.
                  </p>
                </div>
                <div
                  style={{
                    gap: 'var(--dl-space-space-twounits)',
                    width: '100%',
                    display: 'flex',
                    alignItems: 'flex-start',
                    flexDirection: 'column',
                    justifyContent: 'flex-start',
                  }}
                >
                  <div
                    style={{
                      width: '100%',
                      display: 'flex',
                      backgroundColor: '#80FF44',
                    }}
                  >
                    <span
                      style={{
                        color: 'rgb(12, 16, 12)',
                        fontSize: '16px',
                        fontStyle: 'normal',
                        fontFamily: 'Poppins',
                        fontWeight: '500',
                        lineHeight: '24px',
                      }}
                    >
                      <span>Start Enterprise</span>
                      <br></br>
                    </span>
                  </div>
                  <div
                    style={{
                      gap: 'var(--dl-space-space-unit)',
                      display: 'flex',
                      alignItems: 'flex-start',
                      flexDirection: 'column',
                      justifyContent: 'flex-start',
                    }}
                  >
                    <span
                      style={{
                        color: 'rgb(255, 255, 255)',
                        fontStyle: 'normal',
                        fontFamily: 'Poppins',
                        fontWeight: '500',
                        lineHeight: '28px',
                      }}
                    >
                      You will get
                    </span>
                    <div
                      style={{
                        gap: 'var(--dl-space-space-unit)',
                        display: 'flex',
                        alignItems: 'flex-start',
                        flexDirection: 'column',
                        justifyContent: 'flex-start',
                      }}
                    >
                      <Includes rootClassName="rootClassName"></Includes>
                      <Includes rootClassName="rootClassName"></Includes>
                      <Includes rootClassName="rootClassName"></Includes>
                      <Includes rootClassName="rootClassName"></Includes>
                      <Includes rootClassName="rootClassName"></Includes>
                      <Includes rootClassName="rootClassName"></Includes>
                      <Includes rootClassName="rootClassName"></Includes>
                      <Includes rootClassName="rootClassName"></Includes>
                      <Includes rootClassName="rootClassName"></Includes>
                      <Includes rootClassName="rootClassName"></Includes>
                    </div>
                  </div>
                </div>
              </div>
            </main>
          </div>
        </main>
        <div
          style={{
            gap: 'var(--dl-space-space-halfunit)',
            display: 'flex',
            alignItems: 'flex-start',
            flexDirection: 'row',
            justifyContent: 'flex-start',
          }}
        >
          <span
            style={{
              color: '#ffffff',
              fontFamily: 'Poppins',
              lineHeight: '24px',
            }}
          >
            <span>Need any help?</span>
            <br></br>
          </span>
          <div
            style={{
              gap: 'var(--dl-space-space-oneandhalfunits)',
              cursor: 'pointer',
              display: 'flex',
              alignItems: 'center',
              transition: '0.3s',
              borderColor: '#80FF44',
              flexDirection: 'column',
              paddingBottom: 'var(--dl-space-space-halfunit)',
              justifyContent: 'center',
              borderBottomWidth: '1px',
            }}
          >
            <p
              style={{
                color: 'rgb(128, 255, 68)',
                fontStyle: 'normal',
                fontWeight: '500',
                lineHeight: '24px',
              }}
            >
              Contact support -&gt;
            </p>
          </div>
        </div>
      </section>
      <section
        style={{
          gap: 'var(--dl-space-space-fiveunits)',
          flex: '1',
          width: '100%',
          display: 'flex',
          alignItems: 'center',
          paddingTop: '120px',
          borderColor: '#51515A',
          paddingLeft: 'var(--dl-space-space-oneandhalfunits)',
          paddingRight: 'var(--dl-space-space-oneandhalfunits)',
          flexDirection: 'column',
          paddingBottom: '120px',
          borderTopWidth: '1px',
          justifyContent: 'center',
        }}
      >
        <header
          style={{
            gap: 'var(--dl-space-space-unit)',
            width: '100%',
            display: 'flex',
            maxWidth: '1200px',
            alignItems: 'center',
            flexDirection: 'column',
            justifyContent: 'center',
          }}
        >
          <header
            style={{
              gap: 'var(--dl-space-space-oneandhalfunits)',
              width: '100%',
              display: 'flex',
              maxWidth: '600px',
              alignItems: 'center',
              flexDirection: 'column',
              justifyContent: 'center',
            }}
          >
            <span>Tempor incididunt</span>
            <h2
              style={{
                textAlign: 'center',
              }}
            >
              What users say about us
            </h2>
          </header>
          <div
            style={{
              gap: 'var(--dl-space-space-unit)',
              display: 'flex',
              alignItems: 'center',
              flexDirection: 'column',
              justifyContent: 'center',
            }}
          >
            <p
              style={{
                width: '100%',
                maxWidth: '600px',
                textAlign: 'center',
              }}
            >
              Sed ut perspiciatis unde omnis iste natus error sit voluptatem
              accusantium doloremque laudantium, totam rem aperiam.
            </p>
          </div>
        </header>
        <main
          style={{
            width: '100%',
            display: 'grid',
            gridGap: 'var(--dl-space-space-threeunits)',
            maxWidth: '1200px',
            alignItems: 'flex-start',
            flexDirection: 'row',
            gridTemplateColumns: 'auto auto auto',
          }}
        >
          <div
            style={{
              gap: 'var(--dl-space-space-threeunits)',
              display: 'flex',
              flexDirection: 'column',
            }}
          >
            <Review rootClassName="rootClassName"></Review>
            <Review
              Quote="“Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur.\u2028\u2028Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur.”"
              rootClassName="rootClassName"
            ></Review>
          </div>
          <div
            style={{
              gap: 'var(--dl-space-space-threeunits)',
              display: 'flex',
              flexDirection: 'column',
            }}
          >
            <Review
              Quote="“Illum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.”"
              rootClassName="rootClassName"
            ></Review>
            <Review
              Quote="“Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.”"
              rootClassName="rootClassName"
            ></Review>
          </div>
          <div
            style={{
              gap: 'var(--dl-space-space-threeunits)',
              display: 'flex',
              flexDirection: 'column',
            }}
          >
            <Review
              Quote="“Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae.”"
              rootClassName="rootClassName"
            ></Review>
            <Review
              Quote="“Doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae.”"
              rootClassName="rootClassName"
            ></Review>
          </div>
        </main>
        <div
          style={{
            gap: 'var(--dl-space-space-oneandhalfunits)',
            cursor: 'pointer',
            display: 'none',
            alignItems: 'center',
            transition: '0.3s',
            borderColor: '#80FF44',
            flexDirection: 'column',
            paddingBottom: 'var(--dl-space-space-halfunit)',
            justifyContent: 'center',
            borderBottomWidth: '1px',
          }}
        >
          <p
            style={{
              color: 'rgb(128, 255, 68)',
              fontStyle: 'normal',
              fontWeight: '500',
              lineHeight: '24px',
            }}
          >
            View more
          </p>
        </div>
      </section>
      <section
        style={{
          gap: 'var(--dl-space-space-fiveunits)',
          flex: '1',
          width: '100%',
          display: 'flex',
          alignItems: 'center',
          paddingTop: '120px',
          borderColor: '#51515A',
          paddingLeft: 'var(--dl-space-space-oneandhalfunits)',
          paddingRight: 'var(--dl-space-space-oneandhalfunits)',
          flexDirection: 'column',
          paddingBottom: '120px',
          borderTopWidth: '1px',
          justifyContent: 'center',
        }}
      >
        <header
          style={{
            gap: 'var(--dl-space-space-oneandhalfunits)',
            width: '100%',
            display: 'flex',
            maxWidth: '1200px',
            alignItems: 'center',
            flexDirection: 'column',
            justifyContent: 'center',
          }}
        >
          <span>Articles about us</span>
          <h2
            style={{
              textAlign: 'center',
            }}
          >
            We’re the app on everyone’s lips
          </h2>
        </header>
        <main
          style={{
            gap: 'var(--dl-space-space-threeunits)',
            width: '100%',
            display: 'flex',
            maxWidth: '1200px',
            alignItems: 'center',
            flexDirection: 'row',
            justifyContent: 'center',
          }}
        >
          <Article rootClassName="rootClassName"></Article>
          <Article
            Header="techeu"
            SpecialHeader="eu"
            rootClassName="rootClassName"
          ></Article>
          <Article Header="sifted/" rootClassName="rootClassName"></Article>
        </main>
      </section>
      <section
        style={{
          gap: 'var(--dl-space-space-fiveunits)',
          flex: '1',
          width: '100%',
          display: 'flex',
          alignItems: 'center',
          paddingTop: '120px',
          borderColor: '#51515A',
          paddingLeft: 'var(--dl-space-space-oneandhalfunits)',
          paddingRight: 'var(--dl-space-space-oneandhalfunits)',
          flexDirection: 'column',
          paddingBottom: '120px',
          borderTopWidth: '1px',
          justifyContent: 'center',
        }}
      >
        <header
          style={{
            gap: 'var(--dl-space-space-oneandhalfunits)',
            width: '100%',
            display: 'flex',
            maxWidth: '1200px',
            alignItems: 'center',
            flexDirection: 'column',
            justifyContent: 'center',
          }}
        >
          <span>FAQ</span>
          <h2
            style={{
              textAlign: 'center',
            }}
          >
            Frequently asked questions
          </h2>
        </header>
        <main
          style={{
            gap: 'var(--dl-space-space-threeunits)',
            width: '100%',
            display: 'flex',
            maxWidth: '800px',
            alignItems: 'center',
            flexDirection: 'row',
            justifyContent: 'center',
          }}
        >
          <FAQ rootClassName="rootClassName"></FAQ>
        </main>
      </section>
      <section
        style={{
          gap: 'var(--dl-space-space-fiveunits)',
          flex: '1',
          width: '100%',
          display: 'flex',
          alignItems: 'center',
          paddingTop: '120px',
          paddingLeft: 'var(--dl-space-space-oneandhalfunits)',
          paddingRight: 'var(--dl-space-space-oneandhalfunits)',
          flexDirection: 'column',
          justifyContent: 'center',
          backgroundColor: '#292929',
        }}
      >
        <main
          style={{
            width: '100%',
            display: 'flex',
            maxWidth: '1200px',
            position: 'relative',
            alignItems: 'flex-start',
            flexDirection: 'row',
            justifyContent: 'space-between',
          }}
        >
          <header
            style={{
              gap: 'var(--dl-space-space-threeunits)',
              width: '100%',
              display: 'flex',
              maxWidth: '600px',
              alignItems: 'flex-start',
              flexDirection: 'column',
              paddingBottom: '120px',
              justifyContent: 'flex-start',
            }}
          >
            <h2
              style={{
                textAlign: 'left',
              }}
            >
              Stop searching online for medications and use Planical app!
            </h2>
            <div
              style={{
                gap: 'var(--dl-space-space-unit)',
                display: 'flex',
                alignItems: 'center',
                flexDirection: 'row',
                justifyContent: 'center',
              }}
            >
              <div
                style={{
                  gap: 'var(--dl-space-space-halfunit)',
                  display: 'flex',
                  flexDirection: 'row',
                  backgroundColor: '#0F0F0F',
                }}
              >
                <img
                  alt="image"
                  src="/playground_assets/apple-200w.png"
                  style={{
                    width: '16px',
                    objectFit: 'cover',
                  }}
                />
                <span
                  style={{
                    color: '#ffffff',
                    fontSize: '16px',
                    fontStyle: 'normal',
                    fontFamily: 'Poppins',
                    fontWeight: '500',
                    lineHeight: '24px',
                  }}
                >
                  Download for iOS
                </span>
              </div>
              <div
                style={{
                  gap: 'var(--dl-space-space-halfunit)',
                  display: 'flex',
                  flexDirection: 'row',
                  backgroundColor: '#0F0F0F',
                }}
              >
                <img
                  alt="image"
                  src="/playground_assets/android-200h.png"
                  style={{
                    width: '16px',
                    objectFit: 'cover',
                  }}
                />
                <span
                  style={{
                    color: 'rgb(255, 255, 255)',
                    fontSize: '16px',
                    fontStyle: 'normal',
                    fontFamily: 'Poppins',
                    fontWeight: '500',
                    lineHeight: '24px',
                  }}
                >
                  Download for Android
                </span>
              </div>
            </div>
          </header>
          <img
            alt="image"
            src="/playground_assets/group%201505-1200w.png"
            style={{
              right: '0px',
              width: '470px',
              bottom: '0px',
              position: 'absolute',
              objectFit: 'cover',
            }}
          />
        </main>
      </section>
      <footer
        style={{
          gap: 'var(--dl-space-space-fiveunits)',
          flex: '1',
          width: '100%',
          display: 'flex',
          alignItems: 'center',
          paddingTop: '120px',
          paddingLeft: 'var(--dl-space-space-oneandhalfunits)',
          paddingRight: 'var(--dl-space-space-oneandhalfunits)',
          flexDirection: 'column',
          paddingBottom: 'var(--dl-space-space-threeunits)',
          justifyContent: 'center',
        }}
      >
        <div
          style={{
            width: '100%',
            display: 'flex',
            maxWidth: '1200px',
            alignItems: 'flex-start',
            flexDirection: 'row',
            justifyContent: 'space-between',
          }}
        >
          <main
            style={{
              gap: 'var(--dl-space-space-fiveunits)',
              flex: '1',
              height: '100%',
              display: 'flex',
              alignItems: 'flex-start',
              flexDirection: 'column',
              justifyContent: 'flex-start',
            }}
          >
            <div
              style={{
                width: '100%',
                display: 'flex',
                alignItems: 'flex-start',
                flexDirection: 'row',
                justifyContent: 'flex-start',
              }}
            >
              <header
                style={{
                  gap: 'var(--dl-space-space-threeunits)',
                  display: 'flex',
                  alignItems: 'flex-start',
                  flexDirection: 'column',
                  justifyContent: 'center',
                }}
              >
                <div
                  style={{
                    gap: 'var(--dl-space-space-unit)',
                    display: 'flex',
                    alignItems: 'flex-start',
                    flexDirection: 'column',
                    justifyContent: 'center',
                  }}
                >
                  <img
                    alt="image"
                    src="/playground_assets/planical7012-ttpb.svg"
                    style={{
                      width: '120px',
                      objectFit: 'cover',
                    }}
                  />
                  <span
                    style={{
                      color: 'rgb(255, 255, 255)',
                      width: '100%',
                      fontSize: '14px',
                      maxWidth: '260px',
                      fontFamily: 'Poppins',
                      lineHeight: '21px',
                    }}
                  >
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  </span>
                </div>
                <div
                  style={{
                    gap: 'var(--dl-space-space-unit)',
                    width: '100%',
                    display: 'flex',
                    alignItems: 'flex-start',
                    flexDirection: 'row',
                    justifyContent: 'flex-start',
                  }}
                >
                  <a
                    href="https://example.com"
                    target="_blank"
                    rel="noreferrer noopener"
                    style={{
                      display: 'contents',
                    }}
                  >
                    <img
                      alt="image"
                      src="/playground_assets/linkedin-200h.png"
                    />
                  </a>
                  <a
                    href="https://example.com"
                    target="_blank"
                    rel="noreferrer noopener"
                    style={{
                      display: 'contents',
                    }}
                  >
                    <img
                      alt="image"
                      src="/playground_assets/instagram-200h.png"
                    />
                  </a>
                  <a
                    href="https://example.com"
                    target="_blank"
                    rel="noreferrer noopener"
                    style={{
                      display: 'contents',
                    }}
                  >
                    <img
                      alt="image"
                      src="/playground_assets/twitter-200h.png"
                    />
                  </a>
                </div>
              </header>
              <header
                style={{
                  gap: 'var(--dl-space-space-fourunits)',
                  flex: '1',
                  display: 'flex',
                  alignItems: 'flex-start',
                  flexDirection: 'row',
                  justifyContent: 'center',
                }}
              >
                <div
                  style={{
                    gap: 'var(--dl-space-space-unit)',
                    display: 'flex',
                    alignItems: 'flex-start',
                    flexDirection: 'column',
                    justifyContent: 'center',
                  }}
                >
                  <div
                    style={{
                      gap: 'var(--dl-space-space-unit)',
                      display: 'flex',
                      alignItems: 'flex-start',
                      flexDirection: 'column',
                      justifyContent: 'center',
                    }}
                  >
                    <span>Solutions</span>
                  </div>
                  <div
                    style={{
                      gap: 'var(--dl-space-space-unit)',
                      width: '100%',
                      display: 'flex',
                      alignItems: 'flex-start',
                      flexDirection: 'column',
                      justifyContent: 'flex-start',
                    }}
                  >
                    <span>Responsive Web Design</span>
                    <span>Responsive Prototypes</span>
                    <span>Design to Code</span>
                    <span>Static Website Builder</span>
                    <span>Static Website Generator</span>
                  </div>
                </div>
                <div
                  style={{
                    gap: 'var(--dl-space-space-unit)',
                    width: '100%',
                    display: 'flex',
                    maxWidth: '175px',
                    alignItems: 'flex-start',
                    flexDirection: 'column',
                    justifyContent: 'center',
                  }}
                >
                  <div
                    style={{
                      gap: 'var(--dl-space-space-unit)',
                      display: 'flex',
                      alignItems: 'flex-start',
                      flexDirection: 'column',
                      justifyContent: 'center',
                    }}
                  >
                    <span>Company</span>
                  </div>
                  <div
                    style={{
                      gap: 'var(--dl-space-space-unit)',
                      display: 'flex',
                      alignItems: 'flex-start',
                      flexDirection: 'column',
                      justifyContent: 'flex-start',
                    }}
                  >
                    <span>About</span>
                    <span>Team</span>
                    <span>News</span>
                    <span>Partners</span>
                    <span>Careers</span>
                    <span>Press &amp; Media</span>
                  </div>
                </div>
              </header>
            </div>
            <section
              style={{
                gap: 'var(--dl-space-space-fiveunits)',
                flex: '1',
                width: '100%',
                display: 'flex',
                alignItems: 'center',
                flexDirection: 'column',
                justifyContent: 'center',
              }}
            >
              <span
                style={{
                  color: '#C4C4C4',
                  width: '100%',
                  fontSize: '14px',
                  fontFamily: 'Poppins',
                  lineHeight: '21px',
                }}
              >
                © 2022 latitude. All Rights Reserved.
              </span>
            </section>
          </main>
          <main
            style={{
              gap: 'var(--dl-space-space-unit)',
              height: '100%',
              display: 'flex',
              alignItems: 'flex-start',
              flexDirection: 'column',
              justifyContent: 'flex-start',
            }}
          >
            <main
              style={{
                gap: 'var(--dl-space-space-oneandhalfunits)',
                display: 'flex',
                alignItems: 'flex-start',
                flexDirection: 'column',
                justifyContent: 'flex-start',
              }}
            >
              <h1
                style={{
                  color: 'rgb(255, 255, 255)',
                  fontSize: '20px',
                  maxWidth: '275px',
                  fontStyle: 'normal',
                  textAlign: 'left',
                  fontWeight: '500',
                  lineHeight: '30px',
                }}
              >
                Subscribe to our newsletter
              </h1>
              <div
                style={{
                  gap: 'var(--dl-space-space-oneandhalfunits)',
                  display: 'flex',
                  padding: 'var(--dl-space-space-halfunit)',
                  alignItems: 'center',
                  borderRadius: '50px',
                  flexDirection: 'row',
                  justifyContent: 'center',
                  backgroundColor: '#292929',
                }}
              >
                <input
                  type="email"
                  placeholder="Enter your email"
                  style={{
                    flex: '1',
                    color: '#ffffff',
                    height: '24px',
                    lineHeight: '24px',
                    paddingLeft: 'var(--dl-space-space-oneandhalfunits)',
                    outlineStyle: 'none',
                    backgroundColor: 'rgba(217, 217, 217, 0)',
                  }}
                />
                <div
                  style={{
                    display: 'flex',
                    paddingTop: 'var(--dl-space-space-unit)',
                    paddingLeft: 'var(--dl-space-space-oneandhalfunits)',
                    paddingRight: 'var(--dl-space-space-oneandhalfunits)',
                    paddingBottom: 'var(--dl-space-space-unit)',
                    backgroundColor: '#80FF44',
                  }}
                >
                  <span
                    style={{
                      color: 'rgb(12, 16, 12)',
                      display: 'none',
                      fontSize: '16px',
                      fontStyle: 'normal',
                      fontFamily: 'Poppins',
                      fontWeight: '500',
                      lineHeight: '24px',
                    }}
                  >
                    -&gt;
                  </span>
                  <span
                    style={{
                      color: 'rgb(12, 16, 12)',
                      display: 'flex',
                      fontSize: '16px',
                      fontStyle: 'normal',
                      fontFamily: 'Poppins',
                      fontWeight: '500',
                      lineHeight: '24px',
                    }}
                  >
                    <span>Subscribe now</span>
                    <br></br>
                  </span>
                </div>
              </div>
            </main>
            <h1
              style={{
                color: '#686868',
                fontSize: '14px',
                maxWidth: '400px',
                fontStyle: 'normal',
                textAlign: 'left',
                fontWeight: '400',
                lineHeight: '21px',
              }}
            >
              By subscribing to our newsletter you agree with our Terms and
              Conditions.
            </h1>
          </main>
          <section
            style={{
              gap: 'var(--dl-space-space-fiveunits)',
              flex: '1',
              width: '100%',
              display: 'none',
              alignItems: 'center',
              flexDirection: 'column',
              justifyContent: 'center',
            }}
          >
            <span
              style={{
                color: '#C4C4C4',
                width: '100%',
                fontSize: '14px',
                fontFamily: 'Poppins',
                lineHeight: '21px',
              }}
            >
              © 2022 latitude. All Rights Reserved.
            </span>
          </section>
        </div>
      </footer>
      <div>
        <DangerousHTML
          html={`<script>
    /*
Accordion - Code Embed
*/

/* listenForUrlChangesAccordion() makes sure that if you changes pages inside your app,
the Accordions will still work*/

const listenForUrlChangesAccordion = () => {
      let url = location.href;
      document.body.addEventListener(
        "click",
        () => {
          requestAnimationFrame(() => {
            if (url !== location.href) {
              runAccordionCodeEmbed();
              url = location.href;
            }
          });
        },
        true
      );
    };


const runAccordionCodeEmbed = () => {
    const accordionContainers = document.querySelectorAll('[data-role="accordion-container"]'); // All accordion containers
    const accordionContents = document.querySelectorAll('[data-role="accordion-content"]'); // All accordion content
    const accordionIcons = document.querySelectorAll('[data-role="accordion-icon"]'); // All accordion icons

    accordionContents.forEach((accordionContent) => {
        accordionContent.style.display = "none"; //Hides all accordion contents
    });

    accordionContainers.forEach((accordionContainer, index) => {
        accordionContainer.addEventListener("click", () => {
            accordionContents.forEach((accordionContent) => {
            accordionContent.style.display = "none"; //Hides all accordion contents
            });

            accordionIcons.forEach((accordionIcon) => {
                accordionIcon.style.transform = "rotate(0deg)"; // Resets all icon transforms to 0deg (default)
            });

            accordionContents[index].style.display = "flex"; // Shows accordion content
            accordionIcons[index].style.transform = "rotate(180deg)"; // Rotates accordion icon 180deg
        });
    });
}

runAccordionCodeEmbed()
listenForUrlChangesAccordion()

/*
Here's what the above is doing:
    1. Selects all accordion containers, contents, and icons
    2. Hides all accordion contents
    3. Adds an event listener to each accordion container
    4. When an accordion container is clicked, it:
        - Hides all accordion contents
        - Resets all icon transforms to 0deg (default)
        - Checks if this container has class "accordion-open"
            - If it does, it removes class "accordion-open"
            - If it doesn't, it:
                - Removes class "accordion-open" from all containers
                - Adds class "accordion-open" to this container
                - Shows accordion content
                - Rotates accordion icon 180deg
*/
</script>`}
        ></DangerousHTML>
      </div>
    </div>
  )
}

export default Home
