# Web simulation of UbuntuOS
<a href="https://ubuntuos.pages.dev/" target="_blank" style="background: #fff !important; height: 40px !important;width: 140px !important;">Live Site</a>

This is a recreated website of theme Ubuntu 20.04, made using Next.js & Tailwind CSS.
If you want to edit this, Clone this project and edit the files in `/src/components`.

To run this on localhost
type `npm start` and when u are done coding type `npm run build` to build your app.

_NOTE: if you have yarn just replace `npm start` and `npm run build` with `yarn start` and `yarn build`._

<a href="https://www.buymeacoffee.com/vivek9patel" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 40px !important;width: 140px !important;" ></a>

### To make the contact form work

- Create a account in [emailjs](https://www.emailjs.com/) create also new Outlook or Gmail account to be able
  to send email.
- Create a new service, select and log in to your newly created outlook or gmail account on EmailJS.
- Also create a new template, containing the body `Name`: `{{name}}`, `Subject`: `{{subject}}`, `Message`: `{{message}}`.
- Go back to the dashboard and get the Service ID copy it.
- Create a .env file in your root folder and put

```

NEXT_PUBLIC_SERVICE_ID = 'YOUR_SERVICE_ID'
NEXT_PUBLIC_TEMPLATE_ID = 'YOUR_TEMPLATE_ID'
NEXT_PUBLIC_USER_ID = 'YOUR_USER_ID'

```

into it. Replace \*your user id and your service ID with your values in your EmailJS service.
`EmailJS TEMPLATE STRUCTURE`
<img src="https://i.imgur.com/TYvKrdU.png" alt="Template Structure" />

## This project was made using Create Next App! Here is the scripts that u can run.

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.


### `npm run extract`

Used to extract the app for production to the `out` folder.\
It correctly bundles React in production mode into static `HTML` files and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributiors who wants to make this website better can make contribution,which will be **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Added some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request