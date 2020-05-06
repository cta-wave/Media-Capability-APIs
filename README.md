# Media-Capability-APIs

Collects CTA WAVE's comment on W3C Media Capability APIs

The [Media Capabilities API](https://wicg.github.io/media-capabilities/) provides an improved alternative to the 'isTypeSupported()' API for determining whether a given user agent is capable of encoding, decoding and rendering a piece of content.  

To determine if a user-agent can decode a particular piece of content, the 'mediaCapabilities.decodingInfo()' method is called. The method takes an instance of a 'MediaDecodingConfiguration' object as an argument and returns as a 'Promise' a 'MediaCapabilitiesInfo' object.

CTA WAVE has identified several issues when this new API is used with CTA WAVE/CMAF Content. These issues are collected and may be provided to W3C as part of an liaison or other communication channels between CTA WAVE and W3C.
