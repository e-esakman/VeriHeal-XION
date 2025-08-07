## 🧠What is VeriHeal?
VeriHeal is a privacy-preserving health-tech app that empowers individuals to access subsidized, 
stigma-free, or insurance-backed healthcare without compromising their identity or sensitive medical history.

## Project Aim to solve -

While exploring health access challenges, I came across numerous stories and studies 
showing how **insurance systems often fail the most vulnerable** — not due to lack of policies, but due to **discrimination, lack of privacy, or systemic bias**.

- **Elderly patients** are often misled or exploited due to their lack of familiarity / education with insurance terms or digital systems.   
- **LGBTQ+ individuals** report being excluded from insurance or facing biased treatment due to their identity.
- **People with chronic or genetic pre-existing illnesses** struggle to access fair treatment or insurance coverage due to biased algorithms or outdated policies.

### How VeriHeal Helps

1. **Selective Disclosure:**
    Users prove eligibility (e.g., “In Recovery/Suffering from so & so”) without exposing full medical records & enabling support without stigma.
2. **Trustworthy Proofs for Aid:** 
    NGOs, gov programs, or alt-insurers can verify someone's health journey via badges, not invasive data.
3. **Privacy-Preserving Access:**
    VeriHeal replaces “prove your illness” with “prove your effort” , encouraging care-seeking while protecting identity.
4. **Web3-Ready Future:**
    Badges can plug into decentralized health insurance, DAOs, and ZK claim systems unlocking new care models.
    Users can **opt-in anonymously.**


**🌟 Key Features**
1.Privacy-Preserving Access
Users can prove eligibility without revealing personal or medical details

Supports anonymous onboarding and participation

2.Verifiable Health Badges
-Users receive non-invasive proof of effort (e.g., “in recovery”) as NFTs or hashes
-NGOs, alt-insurers, or DAOs can verify without accessing full history

3.Selective Disclosure (ZK Proofs)
-Uses zkTLS to allow eligibility claims without data exposure
-Enables zero-knowledge interactions in health verification

4. Wallet Integration
-Connects to XION wallets using Dave Toolkit SDK
-Designed for decentralized identity and proof-of-claim systems

5. Admin Panel (Planned)
-Admins (doctors, NGOs, or DAO mods) can approve or reject badge applications
-Protects against fake claims while maintaining privacy

6- Web3-Ready Design
All proofs and badges are interoperable with DAOs, claim systems, and decentralized insurance

🌐 Live Links

🔗 Project Submission: https://shorturl.at/B3hOd
📹 Demo Video: https://www.youtube.com/watch?v=O82pc1ZsBcY&feature=youtu.be

🏗️ Architecture
<img width="1424" height="704" alt="Architecture of XION" src="https://github.com/user-attachments/assets/39ebd62e-2103-4b31-97ee-95ec3e90919d" />

### ⚙️ Run Locally

#### 🛠️ Prerequisites
- Node.js
- Expo CLI
- Git

bash
git clone https://github.com/e-esakman/VeriHeal-XION.git
cd VeriHeal-XION

Install dependencies
npm install

Start Expo 
npx expo start

Test Apk yourself!
1. Visit the site to install the App - https://expo.dev/accounts/muffinlearns/projects/VeriHealApp/builds/a708b732-bbe8-4707-aec4-ae29094907b4
OR
2. Scan the QR Code to download it
   <img width="320" height="412" alt="VeriHeal QR code" src="https://github.com/user-attachments/assets/153757b8-b155-4068-9180-7514c62ef9f3" />

## ✅ Project Status

### ✅ Checkpoint 1 (Done)
- ✅ UI screens for splash, onboarding, wallet, and dashboard
- ✅ Mocked UI for login and flow
- ✅ Simulated badge system and zktls verification
- ✅ Expo APK build

### 🚧 Checkpoint 2 (Current)
- 🔄 Email/password + Google OAuth (Supabase)
- 🔄 Real wallet connect (Dave SDK)
- 🔄 Real zktls verification integration
- 🔄 Verifiable badge issuing (NFT/hash style)
- 🔄 Admin panel for badge approval
- 🔄 Onchain proof logic diagrams
- 🔄 GitHub repo live with Supabase schema

### 🧩 Checkpoint 3 (Planned)
- ⏳ Save proof/hash on Badges
- ⏳ Add badge export/share options (QR, URL)
- ⏳ Connect wallet + health logic in Supabase
- ⏳ Build smart contract (optional)
- ⏳ Live MVP demo with DAO interaction


**TECHNOLOGY**  -
| Technology / Tools  |
| ------------------- | --------------------------------------------------------- |
| **Frontend**        | React Native, Expo, Tailwind CSS (via NativeWind)         |
| **Authentication**  | Supabase (Email/Password, Google OAuth)  (2)              |
| **Wallet Connect**  | XION Dave Toolkit SDK (2 + 3)                             |
| **ZK Verification** | zkTLS (Zero-Knowledge TLS Proofs)                         |
| **Badge System**    | NFT-style or hash-based verifiable credentials 
                        (Planned,rn only stimulation)   |                    
| **Build & Deploy**  | Expo Go, QR APK sharing                                   |
| **Version Control** | Git, GitHub                                               |

