# Ex09 Event Registration Web Application
## Date: 21-05-2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
HOME  PAGE
<style>
  .sports-event-container {
    background-color: rgba(21, 221, 239, 1);
    display: flex;
    max-width: 388px;
    flex-direction: column;
    overflow: hidden;
    color: rgba(0, 0, 0, 1);
    text-align: center;
    font: 400 20px Inter, sans-serif;
  }
  .event-wrapper {
    display: flex;
    flex-direction: column;
    position: relative;
    aspect-ratio: 0.733;
    width: 100%;
    align-items: center;
    padding: 10px 10px 26px;
  }
  .background-image {
    position: absolute;
    inset: 0;
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: center;
  }
  .header-image {
    aspect-ratio: 4.93;
    object-fit: contain;
    object-position: center;
    width: 100%;
    align-self: stretch;
  }
  .event-title {
    position: relative;
    margin-top: 47px;
    font: 40px Jim Nightshade, sans-serif;
  }
  .register-button {
    position: relative;
    background-color: rgba(231, 41, 41, 1);
    margin-top: 74px;
    width: 176px;
    max-width: 100%;
    white-space: nowrap;
    padding: 19px 50px;
    cursor: pointer;
    border: none;
    color: inherit;
  }
  .login-button {
    position: relative;
    background-color: rgba(237, 30, 30, 1);
    margin-top: 22px;
    width: 175px;
    max-width: 100%;
    color: rgba(23, 23, 23, 1);
    white-space: nowrap;
    padding: 18px 64px;
    cursor: pointer;
    border: none;
  }
  .event-tagline {
    position: relative;
    color: rgba(12, 231, 235, 1);
    margin-top: 110px;
  }
  .visually-hidden {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
  }
</style>

<div class="sports-event-container">
  <div class="event-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/51d5d8c34bd687ab3e1c9b740151c1292e3deebd98a93bfe6ef17fa19e4ffd74?placeholderIfAbsent=true&apiKey=1629b4e9ef2a424baba4b625fe28bf1c"
      class="background-image"
      alt="Sports Day Event background"
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/cc8b9a843de0f132c033ceebecbf047770d53864bfbd6504bb1e296845104ffb?placeholderIfAbsent=true&apiKey=1629b4e9ef2a424baba4b625fe28bf1c"
      class="header-image"
      alt="Sports Day Event header"
    />
    <h1 class="event-title">Sports Day Event</h1>
    <button class="register-button" tabindex="0">Register</button>
    <button class="login-button" tabindex="0">Login</button>
    <p class="event-tagline">"Born to Win"</p>
  </div>
</div>

EVENT LIST PAGE
<style>
  .sports-events-container {
    background-color: rgba(255, 255, 255, 1);
    display: flex;
    max-width: 384px;
    flex-direction: column;
    overflow: hidden;
    font-family: Inknut Antiqua, sans-serif;
    font-weight: 400;
  }
  .events-wrapper {
    display: flex;
    flex-direction: column;
    position: relative;
    aspect-ratio: 0.726;
    width: 100%;
    padding: 39px 63px 142px;
  }
  .background-image {
    position: absolute;
    inset: 0;
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: center;
  }
  .events-title {
    position: relative;
    color: rgba(244, 26, 26, 1);
    font-size: 20px;
    text-align: center;
    align-self: center;
  }
  .events-list {
    position: relative;
    color: rgba(225, 12, 244, 1);
    font-size: 16px;
    width: 308px;
    margin: 63px 0 -28px;
  }
  .visually-hidden {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
  }
</style>

<div class="sports-events-container">
  <div class="events-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/c3b511e3416f88331ba3fd34c52fa8d8f1927403e4c96b7190ec312f311d0ed7?placeholderIfAbsent=true&apiKey=1629b4e9ef2a424baba4b625fe28bf1c"
      class="background-image"
      alt="Sports day events background"
    />
    <h1 class="events-title">Sports Day Events</h1>
    <div class="events-list" role="list">
      Cricket
      <br />
      Badminton
      <br />
      Volley Ball
      <br />
      100 MTS
      <br />
      200 MTS
      <br />
      400 MTS
      <br />
      4 x 100 Relay
    </div>
  </div>
</div>

REGISTRATION PAGE:
<style>
.registration-container {
  background-color: #fff;
  display: flex;
  max-width: 391px;
  flex-direction: column;
  overflow: hidden;
  color: #000;
  font: 400 14px Inknut Antiqua, sans-serif;
}

.registration-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  aspect-ratio: 0.738;
  width: 100%;
  align-items: start;
  padding: 24px 50px;
}

.background-image {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.form-title {
  position: relative;
  color: rgb(160, 30, 235);
  font-size: 20px;
}

.input-field {
  position: relative;
  background-color: #fff;
  width: 238px;
  max-width: 100%;
  padding: 12px;
}

.input-row {
  position: relative;
  align-self: stretch;
  display: flex;
  gap: 20px;
  justify-content: space-between;
  margin: 10px 0;
}

.input-small {
  background-color: #fff;
  padding: 12px;
}

.submit-button {
  position: relative;
  background-color: rgb(229, 38, 38);
  align-self: center;
  margin-top: 15px;
  width: 210px;
  max-width: 100%;
  color: rgb(23, 23, 23);
  text-align: center;
  padding: 18px;
  font: 20px Inter, sans-serif;
  border: none;
  cursor: pointer;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<form class="registration-container">
  <div class="registration-wrapper">
    <img 
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/96ba9cb8247cb2f170afdd50368f6a0a559a48155b71e81aebadcd3213476a96?placeholderIfAbsent=true&apiKey=1629b4e9ef2a424baba4b625fe28bf1c" 
      alt="" 
      class="background-image"
    />
    <h1 class="form-title">Event Registration Form</h1>
    
    <label for="fullName" class="visually-hidden">Full name</label>
    <input type="text" id="fullName" class="input-field" placeholder="Full name" required />
    
    <div class="input-row">
      <div>
        <label for="gender" class="visually-hidden">Gender</label>
        <select id="gender" class="input-small" required>
          <option value="">Select Gender</option>
          <option value="male">Male</option>
          <option value="female">Female</option>
          <option value="other">Other</option>
        </select>
      </div>
      
      <div>
        <label for="age" class="visually-hidden">Age</label>
        <input type="number" id="age" class="input-small" placeholder="Age" required />
      </div>
    </div>
    
    <label for="regNumber" class="visually-hidden">Registration Number</label>
    <input type="text" id="regNumber" class="input-field" placeholder="Registration Number" required />
    
    <label for="department" class="visually-hidden">Department</label>
    <input type="text" id="department" class="input-field" placeholder="Department" required />
    
    <label for="contact" class="visually-hidden">Contact</label>
    <input type="tel" id="contact" class="input-field" placeholder="Contact" required />
    
    <label for="email" class="visually-hidden">Email</label>
    <input type="email" id="email" class="input-field" placeholder="Email" required />
    
    <label for="events" class="visually-hidden">Events to Register</label>
    <select id="events" class="input-field" required>
      <option value="">Select Events</option>
      <option value="event1">Event 1</option>
      <option value="event2">Event 2</option>
      <option value="event3">Event 3</option>
    </select>
    
    <button type="submit" class="submit-button">Register</button>
  </div>
</form>

THANK YOU PAGE

<style>
.thank-you-section {
  background-color: #fff;
  display: flex;
  max-width: 393px;
  flex-direction: column;
  overflow: hidden;
  color: #000;
  text-align: center;
  font: 700 24px Inter, sans-serif;
}

.content-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  aspect-ratio: 0.746;
  width: 100%;
  align-items: center;
  padding: 17px 30px 84px;
}

.background-image {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.header-image {
  aspect-ratio: 4.83;
  object-fit: contain;
  object-position: center;
  width: 100%;
  align-self: stretch;
}

.title {
  position: relative;
  margin-top: 68px;
}

.message {
  position: relative;
  font-size: 16px;
  margin-top: 42px;
}

.contact-info {
  position: relative;
  color: #2A24D7;
  margin-top: 83px;
}

.email-text {
  font-size: 16px;
}

.contact-detail {
  font-weight: 400;
  font-size: 16px;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="thank-you-section">
  <div class="content-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/375bc7ac81024daa99e30087e446740568b59d020d91bbcb85038c403f242b85?placeholderIfAbsent=true&apiKey=1629b4e9ef2a424baba4b625fe28bf1c"
      class="background-image"
      alt=""
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/765a9013ac633aef9f50d7afa29b31ac8f4cfc731e44224dc10886abe576c919?placeholderIfAbsent=true&apiKey=1629b4e9ef2a424baba4b625fe28bf1c"
      class="header-image"
      alt="Sports event header decoration"
    />
    <h1 class="title">Thank You</h1>
    <p class="message">
      We are all eagerly waiting for your participation in the sports events
    </p>
    <div class="contact-info">
      Contact Us
      <span class="email-text">E-mail:</span>
      <span class="contact-detail">
        saveethaengineeringcollege@gmail.com
      </span>
      <span class="email-text">Phone:</span>
      <span class="contact-detail">7485739332</span>
      <span class="contact-detail">7283928365</span>
    </div>
  </div>
</div>
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/9c84a6ec-34ed-4c2a-88d4-5b7aa0aad7f5)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
