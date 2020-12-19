---
layout: null
---
<head>

<link rel="stylesheet" href="/assets/css/styles.css">
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Lato:wght@300;400;900&display=swap" rel="stylesheet">
<link rel="apple-touch-icon" sizes="180x180" href="/assets/img/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="32x32" href="/assets/img/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/assets/img/favicon-16x16.png">
<link rel="manifest" href="/assets/img/site.webmanifest">
<link rel="mask-icon" href="/assets/img/safari-pinned-tab.svg" color="#5bbad5">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>

html,body {
    margin: 0;
    padding: 0;
    overflow: hidden;
}

#landing-page-wrapper {
  max-width: 600px;
  margin: auto;
	margin-top: 60px;
}

#title h1 {
  margin: 10px 0 10px 0;
  color: #FAECEA;
  font-weight: 900;
  font-size: 5vh;
}

#title h2 {
  margin: 0 0 0 0;
  color: #150605;
  font-weight: 400;
	font-size: 1.5vh;
}
#title {
  margin: 0 auto;
}
#landing-page-nav {
  margin-top: 40vh;
}
#landing-page-nav div {
	margin-top: 10px;
}
#landing-page-nav a {
	text-decoration: none;
	font-weight: 300;
	font-size: 1.5vh;
	color: #150605;
}
#landing-page-nav a:hover {
  font-weight: 400;
}

#landscape {
  position: absolute;
  bottom: 0;
  width: 100%;
}

#landscape svg {
  height: 10vh;
  width: 100%
}

#lower-landscape {
  background-color: #4F1712;
  height: 12vh;
  margin: 0.5vh 0 0 0;
}

@media screen and (max-width: 680px) {
	#landing-page-wrapper {
		margin-left: 40px;
	}
}
@media screen and (max-height: 1024px) {
  #landing-page-nav {
    margin-top: 320px;
  }
	#title h1 {
		font-size: 48px;
	}

	#title h2 {
		font-size: 18px;
	}
	#landing-page-nav a {
		font-size: 18px;
	}
}
@media screen and (max-height: 900px) {
  #landing-page-nav {
    margin-top: 260px;
  }
@media screen and (max-height: 812px) {
  #landing-page-nav {
    margin-top: 240px;
  }
@media screen and (max-height: 768px) {
  #landing-page-nav {
    margin-top: 180px;
  }
}
@media screen and (max-height: 680px) {
  #landing-page-nav {
    margin-top: 120px;
  }
}
@media screen and (max-height: 640px) {
  #landing-page-nav {
    margin-top: 60px;
  }
}

@media screen and (max-height: 560px) {
	#landing-page-wrapper {
		margin-top: 20px;
	}
  #landing-page-nav {
    margin-top: 20px;
  }
	#title h1 {
		font-size: 36px;
	}

	#title h2 {
		font-size: 14px;
	}
	#landing-page-nav a {
		font-size: 14px;
	}
	#landscape svg {
		height: 50px;
	}
  #landing-page-nav div {
    margin-top: 1px;
  }

	#lower-landscape {
		height: 60px;
		margin: 4px 0 0 0;
	}
}
@media screen and (max-height: 400px) {
  #landing-page-nav {
    margin-left: 200px;
    float: left;
  }
  #title {
    float: left;
  }
}
</style>

<html>
    <header>
        <title>caitlin and devon</title>
    </header>
    <body>
      <div id="landing-page-wrapper">
        <div id="title">
            <h1> caitlin </h1>
            <h2> stanley idaho </h2>
            <h2> september 5 2021 </h2>
            <h1> devon </h1>
        </div>
        <div id="landing-page-nav">
        {% for item in site.data.navigation %}
          <div><a href="{{ item.url }}">{{ item.title }}</a></div>
        {% endfor %}
        </div>
      </div>
      <div id="landscape">
          <svg viewBox="0 0 1440 104" fill="none" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M1440 104H0V40.5294L59.8391 29.0588L121.609 45.1176L142.842 62.7059L164.075 52L220.054 50.4706L339.732 19.1176L359.035 21.4118L395.71 17.5882L403.432 21.4118L432.386 14.5294L451.689 19.1176L511.528 8.41177L532.761 7.64706L561.716 18.3529L602.252 3.82353L640.858 0L729.651 16.0588L820.375 12.2353L909.169 25.2353L1005.68 27.5294L1048.15 13.7647L1185.2 16.8235L1231.53 29.0588L1279.79 29.8235L1326.11 37.4706L1374.37 32.1176L1385.95 35.9412L1440 32.1176V104Z" fill="#531813"/>
          </svg>
          <div id="lower-landscape">
              <svg viewBox="0 0 1440 104" fill="none" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M1440 0H0V63.4706L59.8391 74.9412L121.609 58.8824L142.842 41.2941L164.075 52L220.054 53.5294L339.732 84.8824L359.035 82.5882L395.71 86.4118L403.432 82.5882L432.386 89.4706L451.689 84.8824L511.528 95.5882L532.761 96.3529L561.716 85.6471L602.252 100.176L640.858 104L729.651 87.9412L820.375 91.7647L909.169 78.7647L1005.68 76.4706L1048.15 90.2353L1185.2 87.1765L1231.53 74.9412L1279.79 74.1765L1326.11 66.5294L1374.37 71.8824L1385.95 68.0588L1440 71.8824V0Z" fill="#3E120E"/>
              </svg>
          </div>
        </div>
    </body>
</html>
