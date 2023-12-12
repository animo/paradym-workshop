# Role Descriptions

>❗**Important** ❗
>Zero-knowledge proofs only work for number values. Make sure to use the `YYYYMMDD` format when issuing dates, otherwise this won't work.

## Sovereign State Department (Issuer) -- Government

### Background

Guardians of identity, the Sovereign State Department, has been the architect of public documentation for generations. Within its historical walls, every citizen's official journey commences with the issuance of a government ID.

### Credentials to Issue

- **Government ID Credential**:
  - **Full Name**: [e.g., John Doe]
  - **Year of Birth**: Numeric value representing the year of birth [e.g., 1993]
  - **Address**: Full residential address [e.g., 123 Freedom Drive, Capital City]
  - **ID Number**: Unique identification number [e.g., GVT12345678]

## ZKP University (Issuer & Verifier) -- Education

### Background

ZKP University, a cradle of knowledge since the Renaissance, stands as a testament to timeless education. It opens its venerable doors to those who seek wisdom, demanding nothing but a government-sanctioned ID as a token of entry.

### Credentials to Verify

- **Government ID Credential**:
  - **Predicate**: The Year of Birth must be "lessThanOrEqualTo" the current year minus 18 to verify adulthood without revealing the exact date.

### Credentials to Issue

- **Enrollment Credential**:
  - **Student ID**: A unique identifier for the student [e.g., ZKPU123456]
  - **Enrollment Year**: Numeric value representing the year of enrollment [e.g., 2023]
  - **Course of Study**: The field of study or program [e.g., Computer Science]
- **Degree Credential**:
  - **Degree Type**: The level of degree obtained [e.g., Bachelor's]
  - **Field of Study**: The specific area of study [e.g., Software Engineering]
  - **Graduation Year**: Numeric value representing the year of graduation [e.g., 2027]
  - **Cumulative GPA**: Grade point average upon graduation [e.g., 3.7]

## Fit4Life Club (Issuer & Verifier) -- Wellness

### Background

Promoting vitality and vigor, Fit4Life Club remains a sanctuary for those balancing the rigors of academic pursuits with the quest for physical well-being, rewarding the dedication of the enlightened student.

### Credentials to Verify

- **University Enrollment Credential**:
  - **Predicate**: The Enrollment Year must be "greaterThanOrEqualTo" the current year to confirm active enrollment.

### Credentials to Issue

- **Student Discount Membership Credential**:
  - **Membership ID**: A unique identifier for the gym membership [e.g., F4LC789012]
  - **Membership Type**: Type of access granted [e.g., Full, Classes Only]
  - **Valid Through Year**: Numeric value representing the year the membership is valid through [e.g., 2024]

## Innovatech Enterprises (Issuer & Verifier) -- Employment

### Background

At the forefront of innovation, Innovatech Enterprises harnesses the power of intellectual prowess, sculpting a future where technology and human ambition converge.

### Credentials to Verify

- **University Degree Credential**:
  - **Predicate**: The Cumulative GPA must be "greaterThanOrEqualTo" a certain threshold (e.g., 3.0) to ensure the candidate meets the academic standards for the role.

### Credentials to Issue

- **Proof of Employment Credential**:
  - **Employee ID**: Unique identifier within the company [e.g., INN456789]
  - **Position**: Job title or position [e.g., Junior Developer]
  - **Start Year**: Numeric value representing the year employment commenced [e.g., 2023]
  - **Contract Type**: Nature of employment [e.g., Full-time, Part-time, Contract]

## Global Alliance Authority (Issuer & Verifier) -- Immigration

### Background

The Global Alliance Authority stands as the gatekeeper for global talent, enabling the cross-border exchange of skills through a meticulously fair and secure verification process.

### Credentials to Verify

- **Government ID Credential**:
  - **Selective Disclosure**: Verify Full Name and Year of Birth only.
- **University Degree Credential**:
  - **Predicate**: The Graduation Year must be "lessThanOrEqualTo" the current year to ensure the degree is recent.

### Credentials to Issue

- **Work Permit Credential**:
  - **Permit Number**: Unique identifier for the work permit [e.g., WP1234567890]
  - **Valid From Year**: Numeric value representing the year the permit becomes effective [e.g., 2024]
  - **Valid To Year**: Numeric value representing the year the permit expires [e.g., 2026]
  - **Occupation**: Job role or sector allowed [e.g., IT Consultant]

## The Velvet Rope (Verifier) -- Nightlife

### Background

Under the city lights, The Velvet Rope curates exclusive evenings where only the verified can dance the night away, with age and identity as their undisputed pass.

### Credentials to Verify

- **Government ID Credential**:
  - **Predicate**: The Year of Birth must be "lessThanOrEqualTo" the current year minus the legal age for entry to confirm the patron is of legal age.
