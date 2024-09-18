npx create-next-app@latest ./

rm -r .next
npm install
npm cache clean --force

npm i clsx tailwind-merge
npm i tailwindcss-animate

npx shadcn@latest init
npx shadcn@latest add select alert-dialog checkbox command dialog form input-otp input label popover radio-group separator table textarea
npm i react-datepicker

npm install next-themes
npm install react-phone-number-input --save

# 59:24 AppWrite intro https://cloud.appwrite.io/

# add @/lib/appwrite.config.ts

npm install node-appwrite
