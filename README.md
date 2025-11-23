



## 🔧 Getting Started

To get started with the portfolio website:

1. Clone this repository:

   ```bash
   git clone https://github.com/namanbarkiya/minimal-next-portfolio.git personal-portfolio
   cd personal-portfolio
   ```

2. Copy the contents of `.env.copy` to a new `.env` file and fill in the required information.

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your web browser to see the website.



The contact form is integrated with Google Forms for easy message handling. To set it up:
1. Create a Google Form with fields for Name, Email, Message and Social and link to a sheet to collect responses.
2. Get the pre-filled link for the form.
3. Update the `.env` file with the Google Form link and field IDs.
   1. Set `GOOGLE_FORM_LINK` to your Google Form's pre-filled link up to the `usp=pp_url` parameter.
   2. Identify the entry IDs for each field from the pre-filled.


The website traffic is tracked using Google Analytics. To set it up:
1. Set up a property for your portfolio website in Google Analytics.
2. Get the Measurement ID (format: G-XXXXXXXXXX).
3. Update the `.env` file with your Measurement ID.

Lastly, update the resume link in the `.env` file to point to your actual resume.


## 🎨 Customization

The portfolio is designed to be easily customizable:

1. **Personal Information**: Update your personal info in `config/site.ts`
2. **Skills**: Add your skills in `config/skills.ts`
3. **Projects**: Add your technical projects in `config/projects.ts`
4. **Experience**: Customize your professional experience in `config/experience.ts`
5. **Contributions**: Showcase your contributions in `config/contributions.ts`
6. **Colors & Theme**: Modify the theme in `tailwind.config.js`


