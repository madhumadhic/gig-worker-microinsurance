**AI-Powered Parametric Micro-Insurance for Gig Workers**

**1. Problem Statement**

         Gig delivery workers depend on daily and weekly earnings for their livelihood. However, unexpected disruptions such as heavy rain, floods, extreme pollution, curfews, and local restrictions can stop them from working and directly reduce their income. Traditional insurance products are usually not designed for such short-term income loss and often involve complex claim processes.

        This project proposes an AI-powered parametric micro-insurance platform that protects gig workers from weekly income loss caused by external disruptions. The platform uses AI for risk prediction, weekly premium calculation, fraud detection, and automatic claim triggering.

**2. One Line Concept**

          An AI-powered parametric micro-insurance platform that automatically protects gig workers’ weekly income from disruptions like extreme weather, pollution, and curfews.

**3. Target Persona**

        Our primary target users are gig delivery workers operating in urban areas.

Example Persona

       Name: Ravi
       Age: 24
       Occupation: Food delivery partner
       Platform: Swiggy / Zomato
       Location: Chennai – Velachery
       Work Pattern: Works daily for 8–10 hours and depends on daily orders for income

Pain Points

        Income stops during heavy rain and floods

        Unsafe or restricted conditions reduce deliveries

        No quick financial support for temporary work interruptions

        Claiming compensation manually is difficult and slow

**4. Proposed Solution**

            We are building a smart weekly micro-insurance platform for gig workers.

The worker can:

         Register using phone number

         Select work zone

         View AI-based weekly premium

         Buy coverage for one week

         Get automatic payout if a defined disruption occurs

         Track claims and protected earnings through the app

         The system uses parametric insurance, meaning the payout happens automatically when a verified event crosses a predefined threshold.

**5. Why Parametric Insurance**

            Unlike traditional insurance, parametric insurance does not require a long manual claim process. Instead, claims are triggered automatically based on event data.

Example

            If rainfall in a worker’s selected zone is more than 50 mm, the platform automatically verifies the condition and initiates a payout.

This helps:

         reduce claim processing time

         provide faster support

         improve trust for workers

         simplify insurance access for low-income gig workers

**6. Weekly Premium Model**

          The platform follows a weekly micro-insurance model.

| Area Type        | Risk Level  | Weekly Premium |
| ---------------- | ----------- | -------------: |
| Low flood area   | Low Risk    |            ₹10 |
| Heavy rain area  | Medium Risk |            ₹18 |
| Flood-prone zone | High Risk   |            ₹25 |

AI calculates premium based on:

       weather history

       flood zone information

       pollution levels

       disruption frequency in the selected zone

       historical payout probability

Coverage Plans

| Mode    | Weekly Cost | Coverage                  |
| ------- | ----------: | ------------------------- |
| Basic   |         ₹10 | Rain                      |
| Smart   |         ₹18 | Rain + Pollution          |
| Premium |         ₹25 | Rain + Pollution + Curfew |


**7. Parametric Trigger Conditions**
           Claims are automatically triggered when verified disruption conditions occur.

| Event      | Trigger Condition                   | Payout |
| ---------- | ----------------------------------- | -----: |
| Heavy Rain | Rain > 50 mm                        |   ₹200 |
| Flood      | Official flood alert in area        |   ₹300 |
| Pollution  | AQI > 400                           |   ₹150 |
| Curfew     | Government restriction / zone block |   ₹250 |

Claim Flow:

       Worker purchases weekly insurance

       System continuously monitors APIs and zone conditions

       Disruption threshold is crossed

       AI verifies worker zone and activity

       Claim is auto-initiated

       Payout is processed digitally

**8. AI/ML Integration**
       AI is a core part of the solution.

**8.1 AI-Based Risk Prediction**

AI predicts possible risk of income loss using:

        weather forecast API

       flood data

       AQI / pollution data

       traffic and zone activity

       historical disruption records

Example Prediction

        Tomorrow risk in Velachery: 80%
        Reason: Heavy rain forecast
        Suggestion: Activate coverage

**8.2 AI-Based Premium Calculation**
        The system uses risk inputs from the selected zone to dynamically suggest weekly premium rates.

**8.3 Fraud Detection**

AI helps prevent fake claims by checking:

        GPS location consistency

        zone match

        weather/event verification

        delivery activity presence

        repeated abnormal claim patterns

Example Fraud Case

         A worker claims rain disruption, but the weather API shows no heavy rain in that location. The claim is flagged or rejected.

**9. App Workflow**

User Workflow

       User registers with mobile number

       Selects work city and work zone

       AI calculates risk score

       Weekly premium is displayed

       User selects plan and makes payment

       Coverage becomes active

       System monitors disruptions in real time

       If trigger occurs, claim starts automatically

       Fraud check is performed

       Payout is sent

       User tracks claim and protected income in dashboard

**10. Persona-Based Scenarios**

Scenario 1 – Heavy Rain

          Ravi, a food delivery worker in Velachery, buys weekly insurance for ₹18. The next day, heavy rainfall above 50 mm is detected in his work zone. Since the trigger condition is satisfied, the system automatically initiates a ₹200 payout.

Scenario 2 – Flood Alert

          A grocery delivery worker in a flood-prone Chennai zone cannot work because the area is under flood alert. The platform verifies the location and event, then automatically triggers a ₹300 payout.

Scenario 3 – High Pollution

          A worker in a highly polluted zone has active coverage under Smart Mode. AQI crosses 400, making outdoor work unsafe. The system verifies the condition and initiates a ₹150 payout.

11. Platform Choice

          We propose a mobile-first platform because gig workers mainly use smartphones while working. A mobile application makes insurance purchase, claim tracking, and notifications easy and accessible.

          We also plan a simple admin analytics dashboard for insurers or system managers.

12. Main Features
         Worker Mobile App

         Register / Login

         Select work zone

         Buy weekly insurance

         View active coverage

         Claim status tracking

         Earnings protected dashboard

Example Dashboard

         Weekly Premium: ₹15

         Coverage Active: Yes

         Protected Income: ₹1200

         Claims Paid: ₹300

Admin Dashboard

        Total workers insured

        Total claims triggered

        Fraud detection alerts

        High-risk zones

        Daily payout monitoring

Example Admin Insights

        Chennai Rain Claims Today: 120

        Total Payout: ₹24,000

        High-Risk Area: Velachery

**13. Tech Stack**

Frontend

       React / HTML / CSS / JavaScript

       Flutter for mobile prototype (optional)

Backend

       Node.js / Express or Python / Flask

 AI/ML

       Python

       Scikit-learn

APIs

       OpenWeather API

       AQI API

       Mock government curfew / flood alerts

       Mock delivery activity API

Database

       MongoDB / MySQL

Payments

         Razorpay / UPI simulation

**14. Development Plan**

**Phase 1 – Ideation & Foundation**

       Define user persona and problem

       Finalize disruptions and trigger conditions

       Design weekly premium model

       Define AI/ML integration approach

       Create workflow and basic UI plan

       Prepare README and pitch video

**Phase 2 – Automation & Protection**

        Build registration and onboarding

        Develop premium calculator

        Integrate weather and pollution APIs

        Simulate parametric trigger engine

        Implement basic fraud checks

        Create claim automation flow

**Phase 3 – Scale & Optimise**

        Improve AI prediction accuracy

        Enhance dashboard and analytics

        Add more zones and triggers

        Optimize fraud detection logic

        Improve UI and user experience

**15. Minimal Prototype Scope for Phase 1**

For Phase 1, we plan to show:

        onboarding screen

        work zone selection

        premium calculation screen

        coverage plan selection

        disruption trigger simulation

        auto-claim initiation flow

        basic worker dashboard

        basic admin dashboard wireframe

**16. Uniqueness of the Solution**

This solution is unique because it combines:

          weekly low-cost micro-insurance for affordability

          parametric auto-claim system for instant support

          AI-based premium and risk prediction

          fraud detection using API and location validation

          mobile-first design for real gig workers

          dynamic coverage modes such as Basic, Smart, and Premium

**17. Expected Impact**

This platform can help gig workers by:

        protecting short-term earnings

        reducing financial stress during disruptions

        providing fast automated payouts

        improving accessibility to insurance

        creating trust with simple and transparent coverage

**18. Repository Structure**

project-root/
│── README.md
│── docs/
│   ├── workflow.png
│   ├── ui-wireframes.png
│── frontend/
│── backend/
│── ml-model/


**19. Team Vision**

           Our vision is to make insurance simple, fast, affordable, and intelligent for gig workers who face daily uncertainty in their income due to external disruptions.
