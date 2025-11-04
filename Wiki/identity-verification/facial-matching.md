# Facial Matching

## What is Facial Matching?

OkayFace is EMAS eKYC's facial matching component. It compares the live selfie captured during onboarding with the photo on a government-issued ID to confirm both images belong to the same person.

While OkayDoc confirms a document is authentic and OkayLive verifies the user is real, OkayFace answers: "Is this the right person?" This prevents identity theft when fraudsters possess genuine stolen documents. OkayFace achieves 99.50% accuracy with a 0.000001 false match rate, with processing occurring in real-time for instant verification.

## What Problems Does It Solve?

**Stolen Documents Enable Fraud**. Fraudsters obtain genuine ID documents through theft, dark web purchases, or social engineering. Even when businesses verify a document is authentic, they cannot confirm the person presenting it is the legitimate owner. This gap allows criminals to open fraudulent accounts and commit financial crimes.

**Manual Photo Comparison Is Unreliable**. Training staff to compare selfies with ID photos creates bottlenecks and introduces human error. People vary in their ability to recognize faces, especially across different ethnicities or when photos are taken years apart. Manual verification lacks consistency—the same comparison may yield different results depending on who performs the review.

**Security Must Balance with User Experience**. Traditional verification methods require customers to visit physical branches or wait days for manual review, causing application abandonment rates as high as 30%. Companies need instant verification that is both accurate and seamless for legitimate users.

**Regulatory Compliance Requires Documentation**. Financial institutions, telecommunications companies, and other regulated industries must demonstrate they have verified customer identities according to KYC and AML requirements. Manual processes create audit challenges and inconsistent documentation.

## How Businesses Use It

### Financial Services and Digital Banking
Banks and fintech companies integrate OkayFace into mobile apps to verify customer identities during account opening. After a customer uploads their ID document and captures a selfie, OkayFace instantly confirms the match, enabling same-day account activation. This eliminates branch visits and allows digital banks to onboard customers 24/7 while maintaining regulatory compliance.

### Cryptocurrency Exchanges
Crypto platforms use OkayFace to meet KYC regulations while processing thousands of verification requests daily. When users register accounts or increase transaction limits, OkayFace verifies the person matches their submitted identification. This prevents bad actors from using stolen documents to create accounts for money laundering.

### Telecommunications and SIM Registration
Mobile network operators leverage OkayFace at retail locations and online channels to verify customer identities during SIM card registration. Government regulations in many ASEAN countries mandate carriers confirm user identities before activating mobile services. OkayFace enables instant verification at point of sale while preventing SIM swap fraud.

### E-Commerce Platforms
Online marketplaces implement OkayFace to verify seller identities before granting merchant accounts. This reduces fraudulent storefronts, protects buyers from scams, and builds platform trust. High-value transaction platforms also use OkayFace during checkout to prevent account takeover fraud and reduce chargebacks.

### Insurance and Healthcare
Insurance companies use OkayFace during claims processing to verify the person submitting a claim is the actual policyholder. Telehealth platforms verify patient identities before providing medical consultations, ensuring privacy compliance and preventing medical identity fraud.

## Key Benefits

### Operational Efficiency
- **Real-time verification under 1 second**: Eliminate multi-day waiting periods and enable instant customer onboarding
- **Zero manual review required**: Automated AI-powered decisions eliminate dedicated verification teams
- **Process unlimited verifications**: Scale verification capacity instantly during peak demand without additional staff
- **24/7 availability**: Customers complete verification anytime, anywhere

### Enhanced Security
- **99.50% accuracy**: Industry-leading precision using AI algorithms
- **0.000001 false match rate**: Extremely low false positives protect against fraudulent matches
- **Detect stolen identity fraud**: Prevent criminals from using genuine documents that don't belong to them
- **Multi-layer verification**: Works alongside document authentication and liveness detection

### Regulatory Compliance
- **Meet KYC/AML requirements**: Satisfy identity verification obligations across ASEAN markets
- **Complete audit trail**: Automated documentation of every verification decision with confidence scores
- **Consistent application**: Eliminate human bias and ensure every verification follows the same standards
- **Regulatory reporting**: Demonstrate compliance during audits with comprehensive verification records

### Superior Customer Experience
- **Instant results**: Customers receive immediate verification feedback instead of waiting days
- **Mobile-first design**: Seamless experience on smartphones where most digital onboarding occurs
- **Higher conversion rates**: Reduce application abandonment by eliminating lengthy verification delays
- **Accurate verification**: Minimize false rejections that frustrate legitimate customers

## Real-World Examples

### Digital Bank Eliminates Identity Fraud
**Challenge**: A digital-only bank experienced account openings using stolen identity documents. While their document verification detected fake IDs, fraudsters bypassed security using genuine documents purchased on the dark web. The bank faced mounting fraud losses and regulatory scrutiny.

**Solution**: Implemented OkayFace to verify that selfies captured during onboarding matched photos on submitted ID documents. Verification happened instantly within the mobile app with no additional friction for legitimate customers.

**Results**: Prevented $1.8M in fraud losses within the first 6 months. Detected 94% of stolen identity attempts that previously passed document verification. Maintained customer onboarding time under 3 minutes end-to-end while achieving full regulatory compliance.

### Cryptocurrency Exchange Scales Global Verification
**Challenge**: A rapidly growing cryptocurrency exchange needed to verify thousands of new users daily across 15 countries while meeting strict KYC regulations. Manual photo comparison created verification backlogs exceeding 72 hours, causing customer complaints and application abandonment.

**Solution**: Deployed OkayFace as part of their automated verification workflow, processing facial matching for ID documents from multiple countries.

**Results**: Verification time reduced from 72 hours to under 2 minutes. Successfully processed 50,000+ verifications in the first month. Application completion rate increased from 68% to 91%, while detecting and preventing 2,400+ fraudulent account attempts.

## FAQ

**Q: How accurate is facial matching compared to manual review?**
A: OkayFace achieves 99.50% accuracy with a 0.000001 false match rate, significantly outperforming manual review which varies by individual and conditions. Manual comparison accuracy drops below 80% when photos are taken years apart or across different ethnicities, while OkayFace maintains consistent accuracy regardless of these factors.

**Q: How long does the facial matching process take?**
A: Facial matching completes in under 1 second in real-time. The entire verification workflow—including ID capture, liveness check, and facial matching—typically takes less than 2 minutes for customers to complete. There is no waiting period for manual review.

**Q: Can facial matching work with older ID photos?**
A: Yes, OkayFace is designed to match faces even when ID photos are several years old. The AI algorithms account for natural aging, changes in hairstyle, facial hair, and weight fluctuations. It successfully matches photos taken up to 10+ years apart while maintaining high accuracy.

**Q: What happens if someone's appearance has changed significantly?**
A: OkayFace uses advanced algorithms that focus on permanent facial features that don't change with age, weight, or appearance modifications. For extreme cases where legitimate users are rejected, businesses can implement secondary verification flows or manual review escalation paths.

**Q: Is facial matching compliant with privacy regulations?**
A: Yes, OkayFace is compliant with GDPR, PDPA, and other regional privacy regulations. Biometric data is processed securely with encryption, and businesses maintain full control over data retention policies. The system provides audit logs for regulatory reporting and doesn't store biometric templates without explicit consent.

**Q: How does it prevent someone from using a photo of the ID holder?**
A: OkayFace works in conjunction with OkayLive (liveness detection) which ensures the selfie comes from a real person, not a printed photo, video, or deepfake. This multi-layer approach prevents presentation attacks where fraudsters try to use photos or videos of the legitimate ID holder.

**Q: Can it integrate with existing onboarding systems?**
A: Yes, OkayFace offers REST APIs, mobile SDKs (iOS/Android), and webhooks for seamless integration with existing customer onboarding workflows. Most businesses integrate within 2-4 weeks. The solution works with various ID verification platforms, CRM systems, and mobile applications.
