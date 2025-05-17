# 🏃‍♂️ Marathon Hub – B2C Marathon Event Aggregator App

[![View on Play Store](https://img.shields.io/badge/Play%20Store-Marathon%20Hub-green?style=for-the-badge&logo=google-play)](https://play.google.com/store/apps/details?id=com.jumpstart.marathonhub&pcampaignid=web_share)

## 📱 Overview

**Marathon Hub** is a feature-rich B2C Android application designed to digitally connect all stakeholders in the marathon ecosystem — including athletes, coaches, event organizers, physiotherapists, masseurs, and nutritionists. The application acts as a comprehensive event aggregator for marathon events, available on the Google Play Store.

The platform streamlines marathon discovery, event registration, user profiling, and post-event feedback while offering real-time event updates, personalized recommendations, and achievement tracking.

---

## 🌟 Key Features

- 🔐 **User Authentication**
  - Registered users can sign in via email/password
  - New users can register and manage profile details

- 📍 **City-Based Personalization**
  - Users can set preferred cities to receive curated event recommendations and notifications

- 📅 **Event Discovery & Filtering**
  - Upcoming marathon events displayed on the home screen
  - Advanced filters (date, city, price, type) for tailored browsing
  - Save events to an "Interested Events" section for follow-ups

- 📬 **Notifications & Reminders**
  - Timely push notifications for saved events, discount updates, and event reminders using Firebase Cloud Messaging and OneSignal

- 📝 **Event Registration Flow**
  - User enters personal, health, and emergency contact information (one-time entry, editable via profile)
  - Event category selection (e.g., 10k, 20k, 30k), each with unique pricing
  - Seamless integration with Razorpay and PhonePe for secure payments
  - Registered events tracked in the "Registered Events" section

- 🏁 **Post-Event Engagement**
  - Completed events listed under the "Completed Events" section
  - Structured event feedback categorized into pre-run, during-run, and post-run phases using a 1–5 rating system
  - Automated event performance reports generated based on user feedback

- 🏆 **Achievements Sharing**
  - Users can upload running achievements with photos
  - Auto-generated certificate templates for sharing via social platforms

---

## 🛠 Tech Stack

| Category                | Details                                                                 |
|------------------------|-------------------------------------------------------------------------|
| **Language**           | Kotlin                                                                  |
| **UI Design**          | XML with Material 3 Guidelines                                          |
| **Architecture**       | MVVM (Model-View-ViewModel)                                             |
| **Dependency Injection** | Hilt                                                                  |
| **Network Calls**      | Retrofit2 with API Key-based Authentication                             |
| **Local Storage**      | Room Database                                                           |
| **Navigation**         | Single Activity Architecture with Jetpack Navigation Component          |
| **Async Tasks**        | Kotlin Coroutines                                                       |
| **Background Jobs**    | WorkManager (used for tasks like image uploads, PDF generation, etc.)   |
| **Crash Reporting**    | Firebase Crashlytics                                                    |
| **Push Notifications** | Firebase Cloud Messaging + OneSignal Integration                        |

---

## 🔒 Data Handling & Security

- All user data and achievements are securely stored on a remote backend server.
- Sensitive user information such as health and emergency contact details are encrypted and accessible only within authorized application flows.

---

## 📷 UI Screenshots
