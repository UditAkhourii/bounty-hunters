# Bounty Hunters

Bounty Hunters is a real-time vulnerability scanner tool designed specifically for web3 smart contracts. Leveraging the power of Gemma7b model fine-tuned on Hugging Face, coupled with real-time internet access through Google Custom Search and Programmable Search, Bounty Hunters provides an efficient means to scan for vulnerabilities in smart contracts deployed on blockchain networks.

## Features

- Utilizes Gemma7b model fine-tuned for vulnerability detection in web3 smart contracts.
- Connected to real-time internet access via Google Custom Search and Programmable Search.
- Deployed on a WordPress instance to expose the model's API endpoints for public usage.
- Live interface available at [https://apiswitch.tech](https://apiswitch.tech), accessible by creating a free account.
- Rate limit of 10 tests per hour per user for both API and interface usage.
- Comprehensive vulnerability scanning capabilities tailored for smart contracts.

## Resources

- [YouTube Video](https://youtu.be/flBnurC7jtI): Watch a demonstration of the Bounty Hunters model in action.
- [Postman Collection](http://postman.com/bounty-hunters/): Explore and test the API endpoints conveniently using Postman.
- Generic API Key: `eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOjYwMTMsIm5hbWUiOiJzYW1wbGV1c2VyIiwiaWF0IjoxNzEyNDMxMTg0LCJleHAiOjE4NzAxMTExODR9.yBUSr2RJWXT0mHv-Mb54jEECmcQMZFOhNor9tVDLJCU`
- [Project Presentation](https://docs.google.com/presentation/d/1KhYf9Yz-ea49Ao6K7CleXxWpzWBL4S_ae-j2HU1qOWc/edit?usp=sharing): Access the detailed presentation/PPT of the Bounty Hunters project.

## Usage

To use the Bounty Hunters tool, follow these steps:

1. Create a free account on [https://apiswitch.tech](https://apiswitch.tech) to access the live interface.
2. Obtain the generic API key provided above for testing the API endpoints.
3. Use the provided Postman collection to interact with the API and perform vulnerability scans on web3 smart contracts.

OR
1. Create your account
2. Start using the interface and play around with the sample contracts provided. 

## Contributors

- Udit Raj Akhouri (@uditakhourii)
- Ashutosh Kumar (@ashutosh8021)
- Asish Kumar (@Ahambrahmasmi05)

## License

This project is licensed under the [Apache 2.0 License](LICENSE).

## Limitation

This project is currently rate-limited to 10 tests/hour/user.

## Model on HuggingFace

Model is deployed on [Huggingface](https://huggingface.co/uditakhouri/BHT-1-2/) to see the deployed model. 
Please note : This model is not an available to use directly on HuggingFace Inference API becuase we were not able to merge the model due to system compatibility. If you want to try the model, please use our official API at Postman only. [Postman Collection](http://postman.com/bounty-hunters/) (Use the generic API key provided, to make calls).

## Support

For any inquiries or support, please contact [udit_2312res708@iitp.ac.in](mailto:udit_2312res708@iitp.ac.in).

## Acknowledgments

We would like to express our gratitude to the following individuals and organizations for their contributions and support:

- Hugging Face for hosting Gemma7b model and providing fine-tuning capabilities.
- Google for providing access to Custom Search and Programmable Search APIs.
- WordPress for enabling easy deployment of the model's API endpoints.
- The NIT-Patna for inviting us to participate in the hackathon to build Bounty Hunters AI
- All contributors and testers who helped improve the Bounty Hunters tool.
