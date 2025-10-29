# First Mobile App with Expo Router

**Repository:** `prodev-mobile-setup`  
**Directory:** `prodev-mobile-app-0x00`

---

## Objective
To create the first mobile app using the Expo Router template, explore the initial file structure, and test the reset-project command.

---

## Steps Followed

### 1. Navigated to Project Directory
```bash
cd prodev-mobile-setup

2. Initialized the Project
npx create-expo-app@latest .


Selected the latest Expo Router template

Project scaffolding completed successfully

3. Modified the Home Screen

Edited the file:

app/(tabs)/index.tsx


Replaced:

<Text>Welcome!</Text>


with:

<Text>** First App Created**</Text>

4. Ran and Tested the Application
npx expo start


Scanned the QR code using Expo Go (Android)

App loaded and displayed “First App Created”

5. Reset the Project
npm run reset-project

Observations on Reset

.expo folder and build cache were cleared

The app reverted to a clean state, ready for a fresh start

No source files were deleted — only local runtime data was reset

Outcome

✅ Successfully created and tested the first Expo Router app.
✅ Verified that the app runs smoothly on a physical device.
✅ Understood the purpose and effect of the reset-project command.


---

## ✅ **3️⃣ Files to Modify or Include**

| File Path | Description |
|------------|--------------|
| `prodev-mobile-setup/prodev-mobile-app-0x00/README.md` | Your documentation file (content above) |
| `app-example/app/(tabs)/index.tsx` | Replace “Welcome!” with “** First App Created**” |
| `app-example/constants/Colors.tsx` | Leave unchanged (used for styling) |

---