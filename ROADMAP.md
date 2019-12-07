#### 2020 Quarterly Overview
```sh
Q1 - 2020
- Firebase migration
- Android
- Referrals
```

#### Notes
```sh
- Firebase Migration Solves
 - End user security concerns in general
 - OTP
 - Better photo experience to the end user

- Users
 - Firebase auth service is used to manage users
 - During sign up an user is created using firebase auth service and once that is successful, a profile is created for the indian dating domain

- Profiles
 - Profile is owned by lynkUp and all the tags are associated to the profile
 - Profile is associated to a domain
 - An user can have only one profile for each domain

- 7 Sprints and 7 releases - this goes against our decision of 4 releases per year but pushing it to move things quicker
- dates are tentative
```

##### Sprint One - Firebase Migration - Backend deployment and iOS app deployment
```sh
- Firebase migration
 - Each user will have lynkUp auth user credentials and firebase auth user credentials
 - All the user photos will be synced to S3 and firebase storage
 - Backend will depreciate lynkUp auth and will operate using profiles
- Weekly excel reports and daily excel reports - will be on google drive - V1
- Branch IO integration
- App installation analytics
- Customer email interaction tracking
- Infra and Application Monitoring V2
- Matches QA playbook
- Multiple matches to female users
- Storing user device details
- Send emails around approval and rejections
- Improvising matching algo
 - Income
 - ABCD tracker questions
 - Profession based
 - Education tiering
 - Relation preference
 - Relation status
```

##### Sprint Two - Firebase Sync Up & Photo Experience - Backend deployment and iOS app deployment
```sh
- Depreciate lynkUp auth in frontend - total migration to firebase auth
- Depreciate S3 for photos - total migration to firebase storage
- Photo experience - 1 photo, bug fix for Q2
- Chat - more robust, notifications and firebase auth integration
- Customer retention email workflows - V
```

##### Sprint Three - Android, Referral & Lynk Coin - Backend deployment and iOS and android app deployment
```sh
- Migrate to expo 36
- Android stabilization
- Referral
- Lynk Coin with rematch - Unit Economics V0
- Customer retention email workflows - V2
```

##### Sprint Four - Stabilization - Jan 25th Backend deployment and iOS and android app deployment
```sh
- Expo notifications unimodule
- Expo OTA unimodule
- Referral stabilization
- Unit Economics V1
- Pixel Perfection
```

##### Sprint Five - Stabilization & Chat V2 - Backend deployment and iOS and android app deployment
```sh
- Chat V2
- Unit Economics V2
- Weekly excel reports and daily excel reports - will be on google drive - V2
- Migrate to react hooks
- NPS survey
```

##### Sprint Six - Search & New Design - Backend deployment and iOS and android app deployment
```sh
- Search
- Migrate to react navigation 5
- New Design
- Firebase auth with OTP
```

##### Sprint Seven - Search stabilization - Backend deployment and iOS and android app deployment
```sh
- Migrate to expo 37
- Search Stabilization
- Payments - dependent on expo
```
