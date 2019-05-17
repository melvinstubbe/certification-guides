# Implement Azure security (10-15%)

## Implement authentication

- implement authentication by using certificates, forms-based authentication, or tokens
	https://docs.microsoft.com/en-us/azure/active-directory/authentication/active-directory-certificate-based-authentication-get-started
	https://docs.microsoft.com/en-us/azure/active-directory/develop/active-directory-certificate-credentials
- implement multi-factor or Windows authentication by using Azure AD
	https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-mfa-getstarted
	https://docs.microsoft.com/en-us/azure/active-directory/authentication/concept-mfa-howitworks
- implement OAuth2 authentication
	https://docs.microsoft.com/en-us/azure/active-directory/develop/authentication-scenarios
- implement Managed Service Identity (MSI)/Service Principal authentication
	https://docs.microsoft.com/en-us/azure/active-directory/managed-identities-azure-resources/overview
	https://docs.microsoft.com/en-us/azure/active-directory/managed-identities-azure-resources/qs-configure-portal-windows-vm

## Implement access control

- implement CBAC (Claims-Based Access Control) authorization
- implement RBAC (Role-Based Access Control) authorization
	https://docs.microsoft.com/en-us/azure/role-based-access-control/role-assignments-portal
- create shared access signatures
	https://docs.microsoft.com/en-us/azure/storage/common/storage-dotnet-shared-access-signature-part-1

## Implement secure data solutions

- encrypt and decrypt data at rest and in transit
	https://docs.microsoft.com/en-us/azure/cosmos-db/database-encryption-at-rest
- create, read, update, and delete keys, secrets, and certificates by using the KeyVault API
	https://docs.microsoft.com/en-us/azure/key-vault/quick-create-net
	https://docs.microsoft.com/en-us/azure/key-vault/key-vault-manage-with-cli2
	https://docs.microsoft.com/en-us/azure/key-vault/key-vault-overview
