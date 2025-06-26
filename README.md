README
Introduction:
The Blockchain-Powered Organ Donation System is a secure, transparent, and decentralized platform that leverages blockchain technology to streamline the organ donation and transplantation process. By using immutable ledgers and smart contracts, this system ensures data integrity, trust, and traceability in donor-recipient matching, organ availability tracking, and medical verification processes.
Organ donation involves sensitive, life-saving decisions. This system introduces a blockchain layer to eliminate data tampering, improve coordination, and ensure ethical practices across hospitals, registries, and transplant centers.
Objectives:
•	Accessibility:The platform is designed to be user friendly.Easy to Use.
•	Efficiency: Automate Donor-Recipient matching-The system uses technology to match donars and recepiants automatic. This saves time and avoid mistakes
•	Security :The system is designed to keep all data safe.no one can tamper with the information.this ensures sensitive details like dinar and recepiants information stay protected
•	Transparency: Every action or transaction in system will be recorded permanently and can't be altered.this makes the whole process clear and trustworthy 
Hardware & Software Requirements
1.	Multi-core CPU(2.5 GHz+),16-32 GB RAM ,1 TB SSD
2.	Blockchain Platform- Ganache
3.	IDE VS Code




Technologies Used
•	Python – For backend and logic handling
•	Solidity – For writing Ethereum-based smart contracts
•	Web3.py – To connect Python with the Ethereum blockchain
•	Flask – For building a responsive and minimal web interface
•	Ganache – Local blockchain emulator for smart contract testing
•	IPFS – Decentralized file storage for medical records and organ availability logs

Key Modules
1.	Donor/Recipient Registration – Collects details such as name, blood type, organ needed/offered, and medical history.
2.	Match Engine – Finds best matches based on blood type, age, organ type, urgency, and height/weight factors.
3.	Smart Contract Validator – Ensures the match meets medical and ethical criteria.
4.	Blockchain Log Viewer – Displays a history of transactions for transparency.

Results
•	Real-time donor-recipient match verification via smart contracts
•	Immutable record of organ donations and allocations
•	Greater trust among stakeholders through auditability
•	Enhanced privacy and security of patient data

How to Run
Change directory: cd app
Deploy smart contract: truffle compile && truffle migrate
Run the program: npm run dev









