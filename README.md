# Sue

## Project Description
"Sue," derived from and shortened for "Sous Chef," is your culinary companion that suggests personalized recipes after you answer a brief six-question survey. Say goodbye to meal planning uncertainty and elevate your home cooking game with Sue's tailored recommendations, introducing you to dishes you might not have discovered on your own. For recipe inspiration, turn to Sue, your trusty assistant, and let the executive chef within you shine.

## Technologies Used
- **Frontend:** HTML, JS, CSS (mobile first, responsive design), Vite
- **Backend:** Netlify
- **AI Models:** OpenAI (Assistant, Function/Tools, GPT, DALL-E)
- **APIs:** SERP API, Cloudinary CDN

## Installation Instructions
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/sue.git
   cd sue
2. Connect repo to Netlify
   `netlify cli`
4. Install dependencies
   `npm install`
6. Add `OPENAI_API_KEY`, `SERP_API_KEY`, and `asstId` as environment variables
7. Create assistant by referencing assistant-build.txt
8. Add `asstId` as environment variable

## Usage
1. Complete form of questions
2. Click submit
3. Review returned recipes, clicking the tile if you'd like to learn more and cook
4. Reset button to submit a new request

## Future Improvements
We will add in an allergies and dislikes question for Sue to process in order to avoid recommending recipes that a user cannot eat or will not like. This was included in the initial build; however, the assistant could not handle the complexity. This feature can be added in when OpenAI Assistant is more advanced and out of beta or when GPT model improvements are released.

## Contributing
Contributions are welcome! Please follow these guidelines:
- Fork the repository.
- Create a new branch: `git checkout -b feature/new-feature`
- Make your changes and commit them: `git commit -m 'Add new feature'`
- Push to the branch: `git push origin feature/new-feature`
- Submit a pull request.

## Credits
- [OpenAI](https://www.openai.com/)
- [Vite](https://vitejs.dev/)
- [Netlify](https://www.netlify.com/)
- [SERP API](https://serpapi.com/)
- [Cloudinary](https://cloudinary.com/)

## License
This project is open source. [License details](LICENSE)

## Contact Information
- LinkedIn: [Eddie O'Connor](https://www.linkedin.com/in/edwardjamesoconnor/)
- GitHub: [GitHub Profile](https://github.com/Eddie-OConnor)
