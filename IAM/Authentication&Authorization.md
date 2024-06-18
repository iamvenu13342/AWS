<h1>Authentication and Authorization</h1>

<h2>Authentication</h2>

**Definition**: Authentication is the process of verifying the identity of a user, device, or entity attempting to access a system or resource. It ensures that the entity is who or what it claims to be.

<h3>How It Works</h3>

1. **Credentials**: The user provides credentials, which could include:
   
   - **Something they know**: Passwords, PINs, or answers to security questions.
     
   - **Something they have**: Security tokens, smart cards, or mobile phones.
     
   - **Something they are**: Biometric identifiers such as fingerprints, retina scans, or facial recognition.

2. **Verification**: The system checks the provided credentials against a stored database of valid credentials. If the credentials match, the user is authenticated.

**Examples**

- Logging into a computer with a username and password.
  
- Using a fingerprint scanner to unlock a smartphone.
  
- Entering a one-time passcode sent to a mobile device.

<h2>Authorization</h2>

**Definition**: Authorization is the process of determining whether an authenticated user has permission to access a specific resource or perform a particular action. It defines what an authenticated user is allowed to do.

<h3>How It Works</h3>

- **Access Control Policies**: The system checks the user's permissions against predefined access control policies.
   
- **Decision Making**: Based on the policies, the system allows or denies the user’s request to access the resource or perform the action.

**Examples**:

- A user authenticated to a network may have different levels of access to files based on their role (e.g., read-only access vs. read-write access).
- 
- An admin user has the authorization to manage other users, while a regular user does not.
  
- An authenticated user can access certain features of an application based on their subscription level.

<h3>Key Differences</h3>

1. **Purpose**:
   
   - **Authentication**: Confirms the identity of the user.
     
   - **Authorization**: Determines the user's permissions and access rights.

2. **Sequence**:
   
   - **Authentication** occurs first; it verifies the identity.
     
   - **Authorization** follows authentication; it checks permissions.

3. **Components**
   
   - **Authentication**: Involves credentials like passwords, biometrics, or tokens.
     
   - **Authorization**: Involves policies, roles, and rules.

 <h3>Summary</h3>

- **Authentication** answers the question, "Who are you?" It is about verifying the identity of a user or entity.
  
- **Authorization** answers the question, "What can you do?" It is about granting or denying permissions to access resources or perform actions.

Together, authentication and authorization are crucial for securing systems and ensuring that only legitimate users can access the appropriate resources and functionalities.
