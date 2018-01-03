---
-api-id: T:Windows.Networking.NetworkOperators.ESimOperationStatus
-api-type: winrt enum
---

<!-- Enumeration syntax.
public enum ESimOperationStatus : int 
-->

# Windows.Networking.NetworkOperators.ESimOperationStatus

## -description
Defines constants that specify the status of an [ESimOperationResult](esimoperationresult.md) object.

## -enum-fields
### -field Success:0
Indicates that the operation was successful.

### -field NotAuthorized:1
Indicates that the operation was not authorized.

### -field NotFound:2
Indicates that the specified eSIM profile was not found.

### -field PolicyViolation:3
Indicates that the operation violates policy.

### -field InsufficientSpaceOnCard:4
Indicates that there is not enough storage space on the card to complete the operation.

### -field ServerFailure:5
Indicates that a server failure occurred during the operation.

### -field ServerNotReachable:6
Indicates that the server could not be reached during the operation.

### -field TimeoutWaitingForUserConsent:7
Indicates that user consent was not granted within the timeout period of the operation.

### -field IncorrectConfirmationCode:8
Indicates that the wrong confirmation code was supplied during the operation.

### -field ConfirmationCodeMaxRetriesExceeded:9
Indicates that the wrong confirmation code was supplied during the operation, and that no more retries are permitted.

### -field CardNotExist:10
Indicates that the SIM card doesn't exist.

### -field CardBusy:11
Indicates that the SIM card is busy.

### -field Other:12
Indicates a status that's not accounted for by a more specific status.

## -remarks

## -see-also

## -examples

## -capabilities
Microsoft.eSIMManagement_8wekyb3d8bbwe