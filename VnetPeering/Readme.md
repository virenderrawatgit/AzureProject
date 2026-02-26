Azure VNet peering is a networking feature in Microsoft Azure that allows you to connect two or more virtual networks (VNets) seamlessly.
It enables resources in different VNets to communicate with each other as if they were on the same network, using private IP addresses.
Key Features:
  Low-latency, high-bandwidth connection between VNets.
  Private IP communication across VNets.
  No gateway required — traffic does not traverse the public internet.
  Supports both intra-region (same region) and global (cross-region) peering.
  Transitive peering is not supported by default (i.e., VNet A peered with B and B with C doesn’t mean A can talk to C).

Use Cases:
  Connecting different application tiers (e.g., front-end and database) across VNets.
  Linking VNets from different departments or subscriptions.
  Building a hub-and-spoke network topology.
Types of Peering:
  VNet Peering (same region): Connects VNets within the same Azure region.
  Global VNet Peering: Connects VNets across different Azure regions.
