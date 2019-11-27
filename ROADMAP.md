- Users
  - Firebase auth service is used to manage users
  - During sign up an user is create using firebase auth service and once that is successful, a profile is created for the indian dating domain

- Profiles
  - Profile is owned by lynkUp and all the tags are associated to the profile
  - Profile is associated to a domain
  - An user can have only one profile for each domain

7 Sprints and 7 releases - this goes against our decision of 4 releases per year but pushing it to move things quicker

### Sprint One - Firebase Sync up - Dec 13th Backend deployment and iOS app deployment
- Each user will have lynkUp auth user credentials and firebase auth user credentials
- All the user photos will be synced to S3 and firebase storage
- Backend will depreciate lynkUp auth and will operate using profiles
- Weekly excel reports and daily excel reports - will be on google drive - V1
- Branch IO integration
- App installation analytics
- Customer email interaction tracking
- Customer retention email workflows - V1
- Monitoring V2
- Matches QA playbook
- Multiple matches to female users
- User device tracking

### Sprint Two - Firebase Sync Up & Photo Experience - Dec 26th Backend deployment and iOS app deployment
- Depreciate lynkUp auth in frontend - total migration to firebase auth
- Depreciate S3 for photos - total migration to firebase storage
- Photo experience
- Chat - more robust, notifications and firebase auth integration
- Customer retention email workflows - V2

### GA folks will be involved from here

### Sprint Three - Android, Referral & Lynk Coin - Jan 11th Backend deployment and iOS and android app deployment
- Android stabilization
- Referral
- Lynk Coin with rematch - Unit Economics V0

### Sprint Four - Referral & Lynk Coin - Jan 25th Backend deployment and iOS and android app deployment
- Referral stabilization
- Unit Economics V1
- Weekly excel reports and daily excel reports - will be on google drive - V2
- NPS survey

### Sprint Five - Referral & Lynk Coin - Jan 25th Backend deployment and iOS and android app deployment
- Referral stabilization
- Unit Economics V1
- Weekly excel reports and daily excel reports - will be on google drive - V2
- NPS survey
