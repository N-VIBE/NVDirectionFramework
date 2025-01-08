# Convert docc archive to static web page

$(xcrun --find docc) process-archive \
transform-for-static-hosting NVDirectionKit.doccarchive \
--output-path NVDirectionKitStaticWeb.doccarchive \
--hosting-base-path NVDirectionFramework/0.6.1
