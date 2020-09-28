# Tor proposals by number

<!--     DO NOT EDIT THIS FILE     -->

<!-- If you want to make changes here, make sure to edit the -->
<!-- BY_INDEX_TEMPLATE.md file.  The BY_INDEX.md file is -->
<!-- generated by the reindex.py script. -->

Here we have a set of proposals for changes to the Tor protocol.  Some
of these proposals are implemented; some are works in progress; and some
will never be implemented.

Below are a list of proposals sorted by their proposal number.  See
[README.md](/proposals/README.md) for a list of proposals sorted by status.

* [`000-index.txt`](/proposals/000-index.txt): Index of Tor Proposals [META]
* [`001-process.txt`](/proposals/001-process.txt): The Tor Proposal Process [META]
* [`098-todo.txt`](/proposals/098-todo.txt): Proposals that should be written [META]
* [`099-misc.txt`](/proposals/099-misc.txt): Miscellaneous proposals [META]
* [`100-tor-spec-udp.txt`](/proposals/100-tor-spec-udp.txt): Tor Unreliable Datagram Extension Proposal [DEAD]
* [`101-dir-voting.txt`](/proposals/101-dir-voting.txt): Voting on the Tor Directory System [CLOSED]
* [`102-drop-opt.txt`](/proposals/102-drop-opt.txt): Dropping "opt" from the directory format [CLOSED]
* [`103-multilevel-keys.txt`](/proposals/103-multilevel-keys.txt): Splitting identity key from regularly used signing key [CLOSED]
* [`104-short-descriptors.txt`](/proposals/104-short-descriptors.txt): Long and Short Router Descriptors [CLOSED]
* [`105-handshake-revision.txt`](/proposals/105-handshake-revision.txt): Version negotiation for the Tor protocol [CLOSED]
* [`106-less-tls-constraint.txt`](/proposals/106-less-tls-constraint.txt): Checking fewer things during TLS handshakes [CLOSED]
* [`107-uptime-sanity-checking.txt`](/proposals/107-uptime-sanity-checking.txt): Uptime Sanity Checking [CLOSED]
* [`108-mtbf-based-stability.txt`](/proposals/108-mtbf-based-stability.txt): Base "Stable" Flag on Mean Time Between Failures [CLOSED]
* [`109-no-sharing-ips.txt`](/proposals/109-no-sharing-ips.txt): No more than one server per IP address [CLOSED]
* [`110-avoid-infinite-circuits.txt`](/proposals/110-avoid-infinite-circuits.txt): Avoiding infinite length circuits [CLOSED]
* [`111-local-traffic-priority.txt`](/proposals/111-local-traffic-priority.txt): Prioritizing local traffic over relayed traffic [CLOSED]
* [`112-bring-back-pathlencoinweight.txt`](/proposals/112-bring-back-pathlencoinweight.txt): Bring Back Pathlen Coin Weight [SUPERSEDED]
* [`113-fast-authority-interface.txt`](/proposals/113-fast-authority-interface.txt): Simplifying directory authority administration [SUPERSEDED]
* [`114-distributed-storage.txt`](/proposals/114-distributed-storage.txt): Distributed Storage for Tor Hidden Service Descriptors [CLOSED]
* [`115-two-hop-paths.txt`](/proposals/115-two-hop-paths.txt): Two Hop Paths [DEAD]
* [`116-two-hop-paths-from-guard.txt`](/proposals/116-two-hop-paths-from-guard.txt): Two hop paths from entry guards [DEAD]
* [`117-ipv6-exits.txt`](/proposals/117-ipv6-exits.txt): IPv6 exits [CLOSED]
* [`118-multiple-orports.txt`](/proposals/118-multiple-orports.txt): Advertising multiple ORPorts at once [SUPERSEDED]
* [`119-controlport-auth.txt`](/proposals/119-controlport-auth.txt): New PROTOCOLINFO command for controllers [CLOSED]
* [`120-shutdown-descriptors.txt`](/proposals/120-shutdown-descriptors.txt): Shutdown descriptors when Tor servers stop [DEAD]
* [`121-hidden-service-authentication.txt`](/proposals/121-hidden-service-authentication.txt): Hidden Service Authentication [CLOSED]
* [`122-unnamed-flag.txt`](/proposals/122-unnamed-flag.txt): Network status entries need a new Unnamed flag [CLOSED]
* [`123-autonaming.txt`](/proposals/123-autonaming.txt): Naming authorities automatically create bindings [CLOSED]
* [`124-tls-certificates.txt`](/proposals/124-tls-certificates.txt): Blocking resistant TLS certificate usage [SUPERSEDED]
* [`125-bridges.txt`](/proposals/125-bridges.txt): Behavior for bridge users, bridge relays, and bridge authorities [CLOSED]
* [`126-geoip-reporting.txt`](/proposals/126-geoip-reporting.txt): Getting GeoIP data and publishing usage summaries [CLOSED]
* [`127-dirport-mirrors-downloads.txt`](/proposals/127-dirport-mirrors-downloads.txt): Relaying dirport requests to Tor download site / website [OBSOLETE]
* [`128-bridge-families.txt`](/proposals/128-bridge-families.txt): Families of private bridges [DEAD]
* [`129-reject-plaintext-ports.txt`](/proposals/129-reject-plaintext-ports.txt): Block Insecure Protocols by Default [CLOSED]
* [`130-v2-conn-protocol.txt`](/proposals/130-v2-conn-protocol.txt): Version 2 Tor connection protocol [CLOSED]
* [`131-verify-tor-usage.txt`](/proposals/131-verify-tor-usage.txt): Help users to verify they are using Tor [OBSOLETE]
* [`132-browser-check-tor-service.txt`](/proposals/132-browser-check-tor-service.txt): A Tor Web Service For Verifying Correct Browser Configuration [OBSOLETE]
* [`133-unreachable-ors.txt`](/proposals/133-unreachable-ors.txt): Incorporate Unreachable ORs into the Tor Network [RESERVE]
* [`134-robust-voting.txt`](/proposals/134-robust-voting.txt): More robust consensus voting with diverse authority sets [REJECTED]
* [`135-private-tor-networks.txt`](/proposals/135-private-tor-networks.txt): Simplify Configuration of Private Tor Networks [CLOSED]
* [`136-legacy-keys.txt`](/proposals/136-legacy-keys.txt): Mass authority migration with legacy keys [CLOSED]
* [`137-bootstrap-phases.txt`](/proposals/137-bootstrap-phases.txt): Keep controllers informed as Tor bootstraps [CLOSED]
* [`138-remove-down-routers-from-consensus.txt`](/proposals/138-remove-down-routers-from-consensus.txt): Remove routers that are not Running from consensus documents [CLOSED]
* [`139-conditional-consensus-download.txt`](/proposals/139-conditional-consensus-download.txt): Download consensus documents only when it will be trusted [CLOSED]
* [`140-consensus-diffs.txt`](/proposals/140-consensus-diffs.txt): Provide diffs between consensuses [CLOSED]
* [`141-jit-sd-downloads.txt`](/proposals/141-jit-sd-downloads.txt): Download server descriptors on demand [OBSOLETE]
* [`142-combine-intro-and-rend-points.txt`](/proposals/142-combine-intro-and-rend-points.txt): Combine Introduction and Rendezvous Points [DEAD]
* [`143-distributed-storage-improvements.txt`](/proposals/143-distributed-storage-improvements.txt): Improvements of Distributed Storage for Tor Hidden Service Descriptors [SUPERSEDED]
* [`144-enforce-distinct-providers.txt`](/proposals/144-enforce-distinct-providers.txt): Increase the diversity of circuits by detecting nodes belonging the same provider [OBSOLETE]
* [`145-newguard-flag.txt`](/proposals/145-newguard-flag.txt): Separate "suitable as a guard" from "suitable as a new guard" [SUPERSEDED]
* [`146-long-term-stability.txt`](/proposals/146-long-term-stability.txt): Add new flag to reflect long-term stability [SUPERSEDED]
* [`147-prevoting-opinions.txt`](/proposals/147-prevoting-opinions.txt): Eliminate the need for v2 directories in generating v3 directories [REJECTED]
* [`148-uniform-client-end-reason.txt`](/proposals/148-uniform-client-end-reason.txt): Stream end reasons from the client side should be uniform [CLOSED]
* [`149-using-netinfo-data.txt`](/proposals/149-using-netinfo-data.txt): Using data from NETINFO cells [SUPERSEDED]
* [`150-exclude-exit-nodes.txt`](/proposals/150-exclude-exit-nodes.txt): Exclude Exit Nodes from a circuit [CLOSED]
* [`151-path-selection-improvements.txt`](/proposals/151-path-selection-improvements.txt): Improving Tor Path Selection [CLOSED]
* [`152-single-hop-circuits.txt`](/proposals/152-single-hop-circuits.txt): Optionally allow exit from single-hop circuits [CLOSED]
* [`153-automatic-software-update-protocol.txt`](/proposals/153-automatic-software-update-protocol.txt): Automatic software update protocol [SUPERSEDED]
* [`154-automatic-updates.txt`](/proposals/154-automatic-updates.txt): Automatic Software Update Protocol [SUPERSEDED]
* [`155-four-hidden-service-improvements.txt`](/proposals/155-four-hidden-service-improvements.txt): Four Improvements of Hidden Service Performance [CLOSED]
* [`156-tracking-blocked-ports.txt`](/proposals/156-tracking-blocked-ports.txt): Tracking blocked ports on the client side [SUPERSEDED]
* [`157-specific-cert-download.txt`](/proposals/157-specific-cert-download.txt): Make certificate downloads specific [CLOSED]
* [`158-microdescriptors.txt`](/proposals/158-microdescriptors.txt): Clients download consensus + microdescriptors [CLOSED]
* [`159-exit-scanning.txt`](/proposals/159-exit-scanning.txt): Exit Scanning [INFORMATIONAL]
* [`160-bandwidth-offset.txt`](/proposals/160-bandwidth-offset.txt): Authorities vote for bandwidth offsets in consensus [FINISHED]
* [`161-computing-bandwidth-adjustments.txt`](/proposals/161-computing-bandwidth-adjustments.txt): Computing Bandwidth Adjustments [CLOSED]
* [`162-consensus-flavors.txt`](/proposals/162-consensus-flavors.txt): Publish the consensus in multiple flavors [CLOSED]
* [`163-detecting-clients.txt`](/proposals/163-detecting-clients.txt): Detecting whether a connection comes from a client [SUPERSEDED]
* [`164-reporting-server-status.txt`](/proposals/164-reporting-server-status.txt): Reporting the status of server votes [OBSOLETE]
* [`165-simple-robust-voting.txt`](/proposals/165-simple-robust-voting.txt): Easy migration for voting authority sets [REJECTED]
* [`166-statistics-extra-info-docs.txt`](/proposals/166-statistics-extra-info-docs.txt): Including Network Statistics in Extra-Info Documents [CLOSED]
* [`167-params-in-consensus.txt`](/proposals/167-params-in-consensus.txt): Vote on network parameters in consensus [CLOSED]
* [`168-reduce-circwindow.txt`](/proposals/168-reduce-circwindow.txt): Reduce default circuit window [REJECTED]
* [`169-eliminating-renegotiation.txt`](/proposals/169-eliminating-renegotiation.txt): Eliminate TLS renegotiation for the Tor connection handshake [SUPERSEDED]
* [`170-user-path-config.txt`](/proposals/170-user-path-config.txt): Configuration options regarding circuit building [SUPERSEDED]
* [`171-separate-streams.txt`](/proposals/171-separate-streams.txt): Separate streams across circuits by connection metadata [CLOSED]
* [`172-circ-getinfo-option.txt`](/proposals/172-circ-getinfo-option.txt): GETINFO controller option for circuit information [RESERVE]
* [`173-getinfo-option-expansion.txt`](/proposals/173-getinfo-option-expansion.txt): GETINFO Option Expansion [OBSOLETE]
* [`174-optimistic-data-server.txt`](/proposals/174-optimistic-data-server.txt): Optimistic Data for Tor: Server Side [CLOSED]
* [`175-automatic-node-promotion.txt`](/proposals/175-automatic-node-promotion.txt): Automatically promoting Tor clients to nodes [REJECTED]
* [`176-revising-handshake.txt`](/proposals/176-revising-handshake.txt): Proposed version-3 link handshake for Tor [CLOSED]
* [`177-flag-abstention.txt`](/proposals/177-flag-abstention.txt): Abstaining from votes on individual flags [RESERVE]
* [`178-param-voting.txt`](/proposals/178-param-voting.txt): Require majority of authorities to vote for consensus parameters [CLOSED]
* [`179-TLS-cert-and-parameter-normalization.txt`](/proposals/179-TLS-cert-and-parameter-normalization.txt): TLS certificate and parameter normalization [CLOSED]
* [`180-pluggable-transport.txt`](/proposals/180-pluggable-transport.txt): Pluggable transports for circumvention [CLOSED]
* [`181-optimistic-data-client.txt`](/proposals/181-optimistic-data-client.txt): Optimistic Data for Tor: Client Side [CLOSED]
* [`182-creditbucket.txt`](/proposals/182-creditbucket.txt): Credit Bucket [OBSOLETE]
* [`183-refillintervals.txt`](/proposals/183-refillintervals.txt): Refill Intervals [CLOSED]
* [`184-v3-link-protocol.txt`](/proposals/184-v3-link-protocol.txt): Miscellaneous changes for a v3 Tor link protocol [CLOSED]
* [`185-dir-without-dirport.txt`](/proposals/185-dir-without-dirport.txt): Directory caches without DirPort [SUPERSEDED]
* [`186-multiple-orports.txt`](/proposals/186-multiple-orports.txt): Multiple addresses for one OR or bridge [CLOSED]
* [`187-allow-client-auth.txt`](/proposals/187-allow-client-auth.txt): Reserve a cell type to allow client authorization [CLOSED]
* [`188-bridge-guards.txt`](/proposals/188-bridge-guards.txt): Bridge Guards and other anti-enumeration defenses [RESERVE]
* [`189-authorize-cell.txt`](/proposals/189-authorize-cell.txt): AUTHORIZE and AUTHORIZED cells [OBSOLETE]
* [`190-shared-secret-bridge-authorization.txt`](/proposals/190-shared-secret-bridge-authorization.txt): Bridge Client Authorization Based on a Shared Secret [OBSOLETE]
* [`191-mitm-bridge-detection-resistance.txt`](/proposals/191-mitm-bridge-detection-resistance.txt): Bridge Detection Resistance against MITM-capable Adversaries [OBSOLETE]
* [`192-store-bridge-information.txt`](/proposals/192-store-bridge-information.txt): Automatically retrieve and store information about bridges [OBSOLETE]
* [`193-safe-cookie-authentication.txt`](/proposals/193-safe-cookie-authentication.txt): Safe cookie authentication for Tor controllers [CLOSED]
* [`194-mnemonic-urls.txt`](/proposals/194-mnemonic-urls.txt): Mnemonic .onion URLs [SUPERSEDED]
* [`195-TLS-normalization-for-024.txt`](/proposals/195-TLS-normalization-for-024.txt): TLS certificate normalization for Tor 0.2.4.x [DEAD]
* [`196-transport-control-ports.txt`](/proposals/196-transport-control-ports.txt): Extended ORPort and TransportControlPort [FINISHED]
* [`197-postmessage-ipc.txt`](/proposals/197-postmessage-ipc.txt): Message-based Inter-Controller IPC Channel [REJECTED]
* [`198-restore-clienthello-semantics.txt`](/proposals/198-restore-clienthello-semantics.txt): Restore semantics of TLS ClientHello [CLOSED]
* [`199-bridgefinder-integration.txt`](/proposals/199-bridgefinder-integration.txt): Integration of BridgeFinder and BridgeFinderHelper [OBSOLETE]
* [`200-new-create-and-extend-cells.txt`](/proposals/200-new-create-and-extend-cells.txt): Adding new, extensible CREATE, EXTEND, and related cells [CLOSED]
* [`201-bridge-v3-reqs-stats.txt`](/proposals/201-bridge-v3-reqs-stats.txt): Make bridges report statistics on daily v3 network status requests [RESERVE]
* [`202-improved-relay-crypto.txt`](/proposals/202-improved-relay-crypto.txt): Two improved relay encryption protocols for Tor cells [META]
* [`203-https-frontend.txt`](/proposals/203-https-frontend.txt): Avoiding censorship by impersonating an HTTPS server [OBSOLETE]
* [`204-hidserv-subdomains.txt`](/proposals/204-hidserv-subdomains.txt): Subdomain support for Hidden Service addresses [CLOSED]
* [`205-local-dnscache.txt`](/proposals/205-local-dnscache.txt): Remove global client-side DNS caching [CLOSED]
* [`206-directory-sources.txt`](/proposals/206-directory-sources.txt): Preconfigured directory sources for bootstrapping [CLOSED]
* [`207-directory-guards.txt`](/proposals/207-directory-guards.txt): Directory guards [CLOSED]
* [`208-ipv6-exits-redux.txt`](/proposals/208-ipv6-exits-redux.txt): IPv6 Exits Redux [CLOSED]
* [`209-path-bias-tuning.txt`](/proposals/209-path-bias-tuning.txt): Tuning the Parameters for the Path Bias Defense [OBSOLETE]
* [`210-faster-headless-consensus-bootstrap.txt`](/proposals/210-faster-headless-consensus-bootstrap.txt): Faster Headless Consensus Bootstrapping [SUPERSEDED]
* [`211-mapaddress-tor-status.txt`](/proposals/211-mapaddress-tor-status.txt): Internal Mapaddress for Tor Configuration Testing [RESERVE]
* [`212-using-old-consensus.txt`](/proposals/212-using-old-consensus.txt): Increase Acceptable Consensus Age [NEEDS-REVISION]
* [`213-remove-stream-sendmes.txt`](/proposals/213-remove-stream-sendmes.txt): Remove stream-level sendmes from the design [DEAD]
* [`214-longer-circids.txt`](/proposals/214-longer-circids.txt): Allow 4-byte circuit IDs in a new link protocol [CLOSED]
* [`215-update-min-consensus-ver.txt`](/proposals/215-update-min-consensus-ver.txt): Let the minimum consensus method change with time [CLOSED]
* [`216-ntor-handshake.txt`](/proposals/216-ntor-handshake.txt): Improved circuit-creation key exchange [CLOSED]
* [`217-ext-orport-auth.txt`](/proposals/217-ext-orport-auth.txt): Tor Extended ORPort Authentication [FINISHED]
* [`218-usage-controller-events.txt`](/proposals/218-usage-controller-events.txt): Controller events to better understand connection/circuit usage [CLOSED]
* [`219-expanded-dns.txt`](/proposals/219-expanded-dns.txt): Support for full DNS and DNSSEC resolution in Tor [NEEDS-REVISION]
* [`220-ecc-id-keys.txt`](/proposals/220-ecc-id-keys.txt): Migrate server identity keys to Ed25519 [CLOSED]
* [`221-stop-using-create-fast.txt`](/proposals/221-stop-using-create-fast.txt): Stop using CREATE_FAST [CLOSED]
* [`222-remove-client-timestamps.txt`](/proposals/222-remove-client-timestamps.txt): Stop sending client timestamps [CLOSED]
* [`223-ace-handshake.txt`](/proposals/223-ace-handshake.txt): Ace: Improved circuit-creation key exchange [RESERVE]
* [`224-rend-spec-ng.txt`](/proposals/224-rend-spec-ng.txt): Next-Generation Hidden Services in Tor [CLOSED]
* [`225-strawman-shared-rand.txt`](/proposals/225-strawman-shared-rand.txt): Strawman proposal: commit-and-reveal shared rng [SUPERSEDED]
* [`226-bridgedb-database-improvements.txt`](/proposals/226-bridgedb-database-improvements.txt): "Scalability and Stability Improvements to BridgeDB: Switching to a Distributed Database System and RDBMS" [RESERVE]
* [`227-vote-on-package-fingerprints.txt`](/proposals/227-vote-on-package-fingerprints.txt): Include package fingerprints in consensus documents [CLOSED]
* [`228-cross-certification-onionkeys.txt`](/proposals/228-cross-certification-onionkeys.txt): Cross-certifying identity keys with onion keys [CLOSED]
* [`229-further-socks5-extensions.txt`](/proposals/229-further-socks5-extensions.txt): Further SOCKS5 extensions [REJECTED]
* [`230-rsa1024-relay-id-migration.txt`](/proposals/230-rsa1024-relay-id-migration.txt): How to change RSA1024 relay identity keys [OBSOLETE]
* [`231-migrate-authority-rsa1024-ids.txt`](/proposals/231-migrate-authority-rsa1024-ids.txt): Migrating authority RSA1024 identity keys [OBSOLETE]
* [`232-pluggable-transports-through-proxy.txt`](/proposals/232-pluggable-transports-through-proxy.txt): Pluggable Transport through SOCKS proxy [FINISHED]
* [`233-quicken-tor2web-mode.txt`](/proposals/233-quicken-tor2web-mode.txt): Making Tor2Web mode faster [REJECTED]
* [`234-remittance-addresses.txt`](/proposals/234-remittance-addresses.txt): Adding remittance field to directory specification [REJECTED]
* [`235-kill-named-flag.txt`](/proposals/235-kill-named-flag.txt): Stop assigning (and eventually supporting) the Named flag [CLOSED]
* [`236-single-guard-node.txt`](/proposals/236-single-guard-node.txt): The move to a single guard node [CLOSED]
* [`237-directory-servers-for-all.txt`](/proposals/237-directory-servers-for-all.txt): All relays are directory servers [CLOSED]
* [`238-hs-relay-stats.txt`](/proposals/238-hs-relay-stats.txt): Better hidden service stats from Tor relays [CLOSED]
* [`239-consensus-hash-chaining.txt`](/proposals/239-consensus-hash-chaining.txt): Consensus Hash Chaining [OPEN]
* [`240-auth-cert-revocation.txt`](/proposals/240-auth-cert-revocation.txt): Early signing key revocation for directory authorities [OPEN]
* [`241-suspicious-guard-turnover.txt`](/proposals/241-suspicious-guard-turnover.txt): Resisting guard-turnover attacks [REJECTED]
* [`242-better-families.txt`](/proposals/242-better-families.txt): Better performance and usability for the MyFamily option [RESERVE]
* [`243-hsdir-flag-need-stable.txt`](/proposals/243-hsdir-flag-need-stable.txt): Give out HSDir flag only to relays with Stable flag [CLOSED]
* [`244-use-rfc5705-for-tls-binding.txt`](/proposals/244-use-rfc5705-for-tls-binding.txt): Use RFC5705 Key Exporting in our AUTHENTICATE calls [CLOSED]
* [`245-tap-out.txt`](/proposals/245-tap-out.txt): Deprecating and removing the TAP circuit extension protocol [NEEDS-REVISION]
* [`246-merge-hsdir-and-intro.txt`](/proposals/246-merge-hsdir-and-intro.txt): Merging Hidden Service Directories and Introduction Points [REJECTED]
* [`247-hs-guard-discovery.txt`](/proposals/247-hs-guard-discovery.txt): Defending Against Guard Discovery Attacks using Vanguards [SUPERSEDED]
* [`248-removing-rsa-identities.txt`](/proposals/248-removing-rsa-identities.txt): Remove all RSA identity keys [NEEDS-REVISION]
* [`249-large-create-cells.txt`](/proposals/249-large-create-cells.txt): Allow CREATE cells with >505 bytes of handshake data [SUPERSEDED]
* [`250-commit-reveal-consensus.txt`](/proposals/250-commit-reveal-consensus.txt): Random Number Generation During Tor Voting [CLOSED]
* [`251-netflow-padding.txt`](/proposals/251-netflow-padding.txt): Padding for netflow record resolution reduction [CLOSED]
* [`252-single-onion.txt`](/proposals/252-single-onion.txt): Single Onion Services [SUPERSEDED]
* [`253-oob-hmac.txt`](/proposals/253-oob-hmac.txt): Out of Band Circuit HMACs [DEAD]
* [`254-padding-negotiation.txt`](/proposals/254-padding-negotiation.txt): Padding Negotiation [CLOSED]
* [`255-hs-load-balancing.txt`](/proposals/255-hs-load-balancing.txt): Controller features to allow for load-balancing hidden services [RESERVE]
* [`256-key-revocation.txt`](/proposals/256-key-revocation.txt): Key revocation for relays and authorities [RESERVE]
* [`257-hiding-authorities.txt`](/proposals/257-hiding-authorities.txt): Refactoring authorities and making them more isolated from the net [META]
* [`258-dirauth-dos.txt`](/proposals/258-dirauth-dos.txt): Denial-of-service resistance for directory authorities [DEAD]
* [`259-guard-selection.txt`](/proposals/259-guard-selection.txt): New Guard Selection Behaviour [OBSOLETE]
* [`260-rend-single-onion.txt`](/proposals/260-rend-single-onion.txt): Rendezvous Single Onion Services [FINISHED]
* [`261-aez-crypto.txt`](/proposals/261-aez-crypto.txt): AEZ for relay cryptography [OBSOLETE]
* [`262-rekey-circuits.txt`](/proposals/262-rekey-circuits.txt): Re-keying live circuits with new cryptographic material [RESERVE]
* [`263-ntru-for-pq-handshake.txt`](/proposals/263-ntru-for-pq-handshake.txt): Request to change key exchange protocol for handshake v1.2 [OBSOLETE]
* [`264-subprotocol-versions.txt`](/proposals/264-subprotocol-versions.txt): Putting version numbers on the Tor subprotocols [CLOSED]
* [`265-load-balancing-with-overhead.txt`](/proposals/265-load-balancing-with-overhead.txt): Load Balancing with Overhead Parameters [ACCEPTED]
* [`266-removing-current-obsolete-clients.txt`](/proposals/266-removing-current-obsolete-clients.txt): Removing current obsolete clients from the Tor network [SUPERSEDED]
* [`267-tor-consensus-transparency.txt`](/proposals/267-tor-consensus-transparency.txt): Tor Consensus Transparency [OPEN]
* [`268-guard-selection.txt`](/proposals/268-guard-selection.txt): New Guard Selection Behaviour [OBSOLETE]
* [`269-hybrid-handshake.txt`](/proposals/269-hybrid-handshake.txt): Transitionally secure hybrid handshakes [NEEDS-REVISION]
* [`270-newhope-hybrid-handshake.txt`](/proposals/270-newhope-hybrid-handshake.txt): RebelAlliance: A Post-Quantum Secure Hybrid Handshake Based on NewHope [OBSOLETE]
* [`271-another-guard-selection.txt`](/proposals/271-another-guard-selection.txt): Another algorithm for guard selection [CLOSED]
* [`272-valid-and-running-by-default.txt`](/proposals/272-valid-and-running-by-default.txt): Listed routers should be Valid, Running, and treated as such [CLOSED]
* [`273-exit-relay-pinning.txt`](/proposals/273-exit-relay-pinning.txt): Exit relay pinning for web services [DRAFT]
* [`274-rotate-onion-keys-less.txt`](/proposals/274-rotate-onion-keys-less.txt): Rotate onion keys less frequently [CLOSED]
* [`275-md-published-time-is-silly.txt`](/proposals/275-md-published-time-is-silly.txt): Stop including meaningful "published" time in microdescriptor consensus [ACCEPTED]
* [`276-lower-bw-granularity.txt`](/proposals/276-lower-bw-granularity.txt): Report bandwidth with lower granularity in consensus documents [DEAD]
* [`277-detect-id-sharing.txt`](/proposals/277-detect-id-sharing.txt): Detect multiple relay instances running with same ID [OPEN]
* [`278-directory-compression-scheme-negotiation.txt`](/proposals/278-directory-compression-scheme-negotiation.txt): Directory Compression Scheme Negotiation [CLOSED]
* [`279-naming-layer-api.txt`](/proposals/279-naming-layer-api.txt): A Name System API for Tor Onion Services [NEEDS-REVISION]
* [`280-privcount-in-tor.txt`](/proposals/280-privcount-in-tor.txt): Privacy-Preserving Statistics with Privcount in Tor [SUPERSEDED]
* [`281-bulk-md-download.txt`](/proposals/281-bulk-md-download.txt): Downloading microdescriptors in bulk [RESERVE]
* [`282-remove-named-from-consensus.txt`](/proposals/282-remove-named-from-consensus.txt): Remove "Named" and "Unnamed" handling from consensus voting [FINISHED]
* [`283-ipv6-in-micro-consensus.txt`](/proposals/283-ipv6-in-micro-consensus.txt): Move IPv6 ORPorts from microdescriptors to the microdesc consensus [CLOSED]
* [`284-hsv3-control-port.txt`](/proposals/284-hsv3-control-port.txt): Hidden Service v3 Control Port [CLOSED]
* [`285-utf-8.txt`](/proposals/285-utf-8.txt): Directory documents should be standardized as UTF-8 [ACCEPTED]
* [`286-hibernation-api.txt`](/proposals/286-hibernation-api.txt): Controller APIs for hibernation access on mobile [REJECTED]
* [`287-reduce-lifetime.txt`](/proposals/287-reduce-lifetime.txt): Reduce circuit lifetime without overloading the network [OPEN]
* [`288-privcount-with-shamir.txt`](/proposals/288-privcount-with-shamir.txt): Privacy-Preserving Statistics with Privcount in Tor (Shamir version) [ACCEPTED]
* [`289-authenticated-sendmes.txt`](/proposals/289-authenticated-sendmes.txt): Authenticating sendme cells to mitigate bandwidth attacks [CLOSED]
* [`290-deprecate-consensus-methods.txt`](/proposals/290-deprecate-consensus-methods.txt): Continuously update consensus methods [META]
* [`291-two-guard-nodes.txt`](/proposals/291-two-guard-nodes.txt): The move to two guard nodes [NEEDS-REVISION]
* [`292-mesh-vanguards.txt`](/proposals/292-mesh-vanguards.txt): Mesh-based vanguards [ACCEPTED]
* [`293-know-when-to-publish.txt`](/proposals/293-know-when-to-publish.txt): Other ways for relays to know when to publish [CLOSED]
* [`294-tls-1.3.txt`](/proposals/294-tls-1.3.txt): TLS 1.3 Migration [DRAFT]
* [`295-relay-crypto-with-adl.txt`](/proposals/295-relay-crypto-with-adl.txt): Using ADL for relay cryptography (solving the crypto-tagging attack) [OPEN]
* [`296-expose-bandwidth-files.txt`](/proposals/296-expose-bandwidth-files.txt): Have Directory Authorities expose raw bandwidth list files [OPEN]
* [`297-safer-protover-shutdowns.txt`](/proposals/297-safer-protover-shutdowns.txt): Relaxing the protover-based shutdown rules [CLOSED]
* [`298-canonical-families.txt`](/proposals/298-canonical-families.txt): Putting family lines in canonical form [CLOSED]
* [`299-ip-failure-count.txt`](/proposals/299-ip-failure-count.txt): Preferring IPv4 or IPv6 based on IP Version Failure Count [SUPERSEDED]
* [`300-walking-onions.txt`](/proposals/300-walking-onions.txt): Walking Onions: Scaling and Saving Bandwidth [INFORMATIONAL]
* [`301-dont-vote-on-package-fingerprints.txt`](/proposals/301-dont-vote-on-package-fingerprints.txt): Don't include package fingerprints in consensus documents [FINISHED]
* [`302-padding-machines-for-onion-clients.txt`](/proposals/302-padding-machines-for-onion-clients.txt): Hiding onion service clients using padding [CLOSED]
* [`303-protover-removal-policy.txt`](/proposals/303-protover-removal-policy.txt): When and how to remove support for protocol versions [OPEN]
* [`304-socks5-extending-hs-error-codes.txt`](/proposals/304-socks5-extending-hs-error-codes.txt): Extending SOCKS5 Onion Service Error Codes [CLOSED]
* [`305-establish-intro-dos-defense-extention.txt`](/proposals/305-establish-intro-dos-defense-extention.txt): ESTABLISH_INTRO Cell DoS Defense Extension [CLOSED]
* [`306-ipv6-happy-eyeballs.txt`](/proposals/306-ipv6-happy-eyeballs.txt): A Tor Implementation of IPv6 Happy Eyeballs [OPEN]
* [`307-onionbalance-v3.txt`](/proposals/307-onionbalance-v3.txt): Onion Balance Support for Onion Service v3 [RESERVE]
* [`308-counter-galois-onion.txt`](/proposals/308-counter-galois-onion.txt): Counter Galois Onion: A New Proposal for Forward-Secure Relay Cryptography [OPEN]
* [`309-optimistic-socks-in-tor.txt`](/proposals/309-optimistic-socks-in-tor.txt): Optimistic SOCKS Data [OPEN]
* [`310-bandaid-on-guard-selection.txt`](/proposals/310-bandaid-on-guard-selection.txt): Towards load-balancing in Prop 271 [FINISHED]
* [`311-relay-ipv6-reachability.txt`](/proposals/311-relay-ipv6-reachability.txt): Tor Relay IPv6 Reachability [ACCEPTED]
* [`312-relay-auto-ipv6-addr.txt`](/proposals/312-relay-auto-ipv6-addr.txt): Tor Relay Automatic IPv6 Address Discovery [ACCEPTED]
* [`313-relay-ipv6-stats.txt`](/proposals/313-relay-ipv6-stats.txt): Tor Relay IPv6 Statistics [ACCEPTED]
* [`314-allow-markdown-proposals.md`](/proposals/314-allow-markdown-proposals.md): Allow Markdown for proposal format [FINISHED]
* [`315-update-dir-required-fields.txt`](/proposals/315-update-dir-required-fields.txt): Updating the list of fields required in directory documents [OPEN]
* [`316-flashflow.md`](/proposals/316-flashflow.md): FlashFlow: A Secure Speed Test for Tor (Parent Proposal) [DRAFT]
* [`317-secure-dns-name-resolution.txt`](/proposals/317-secure-dns-name-resolution.txt): Improve security aspects of DNS name resolution [NEEDS-REVISION]
* [`318-limit-protovers.md`](/proposals/318-limit-protovers.md): Limit protover values to 0-63 [ACCEPTED]
* [`319-wide-everything.md`](/proposals/319-wide-everything.md): RELAY_FRAGMENT cells [OPEN]
* [`320-tap-out-again.md`](/proposals/320-tap-out-again.md): Removing TAP usage from v2 onion services [REJECTED]
* [`321-happy-families.md`](/proposals/321-happy-families.md): Better performance and usability for the MyFamily option (v2) [OPEN]
* [`322-dirport-linkspec.md`](/proposals/322-dirport-linkspec.md): Extending link specifiers to include the directory port [OPEN]
* [`323-walking-onions-full.md`](/proposals/323-walking-onions-full.md): Specification for Walking Onions [OPEN]
* [`324-rtt-congestion-control.txt`](/proposals/324-rtt-congestion-control.txt): RTT-based Congestion Control for Tor [OPEN]
* [`325-packed-relay-cells.md`](/proposals/325-packed-relay-cells.md): Packed relay cells: saving space on small commands [OPEN]
* [`326-tor-relay-well-known-uri-rfc8615.md`](/proposals/326-tor-relay-well-known-uri-rfc8615.md): The "tor-relay" Well-Known Resource Identifier [OPEN]
* [`327-pow-over-intro.txt`](/proposals/327-pow-over-intro.txt): A First Take at PoW Over Introduction Circuits [DRAFT]
