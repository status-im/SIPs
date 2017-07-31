This is the suggested template for new SIPs.

Note that an SIP number will be assigned by an editor. When opening a pull request to submit your SIP, please use an abbreviated title in the filename, `eip-draft_title_abbrev.md`.

## Preamble

    SIP: <to be assigned>
    Title: <SIP title>
    Author: <list of authors' names and optionally, email addresses>
    Type: <Standard Track | Informational | Meta>
    Category (*only required for Standard Track): <Core | Networking | Interface | ERC> 
    Status: Draft
    Created: <date created on, in ISO 8601 (yyyy-mm-dd) format>
    Requires (*optional): <SIP number(s)>
    Replaces (*optional): <SIP number(s)>


## Simple Summary
"If you can't explain it simply, you don't understand it well enough." Provide a simplified and layman-accessible explanation of the SIP.

## Abstract
A short (~200 word) description of the technical issue being addressed.

## Motivation
The motivation is critical for SIPs that want to change Status. It should clearly explain why the existing protocol specification is inadequate to address the problem that the SIP solves. SIP submissions without sufficient motivation may be rejected outright.

## Specification
The technical specification should describe the syntax and semantics of any new feature. The specification should be detailed enough to allow competing, interoperable implementations for any of the current Status software (status-go, status-react, status-network, react-native-qt, etc ... ). 

## Rationale
The rationale fleshes out the specification by describing what motivated the design and why particular design decisions were made. It should describe alternate designs that were considered and related work, e.g. how the feature is supported in other languages. The rationale may also provide evidence of consensus within the community, and should discuss important objections or concerns raised during discussion.

## Backwards Compatibility
All SIPs that introduce backwards incompatibilities must include a section describing these incompatibilities and their severity. The SIP must explain how the author proposes to deal with these incompatibilities. SIP submissions without a sufficient backwards compatibility treatise may be rejected outright.

## Test Cases
Test cases for an implementation are mandatory for SIPs that are affecting consensus changes. Other SIPs can choose to include links to test cases if applicable.

## Implementation
The implementations must be completed before any SIP is given status "Final", but it need not be completed before the SIP is accepted. While there is merit to the approach of reaching consensus on the specification and rationale before writing code, the principle of "rough consensus and running code" is still useful when it comes to resolving many discussions of API details.

## Copyright
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
