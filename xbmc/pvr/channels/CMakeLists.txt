set(SOURCES PVRChannel.cpp
            PVRChannelGroup.cpp
            PVRChannelGroupAllChannels.cpp
            PVRChannelGroupFromClient.cpp
            PVRChannelGroupFromUser.cpp
            PVRChannelGroupMember.cpp
            PVRChannelGroupSettings.cpp
            PVRChannelGroups.cpp
            PVRChannelGroupsContainer.cpp
            PVRChannelNumber.cpp
            PVRRadioRDSInfoTag.cpp
            PVRChannelsPath.cpp)

set(HEADERS PVRChannel.h
            PVRChannelGroup.h
            PVRChannelGroupAllChannels.h
            PVRChannelGroupFromClient.h
            PVRChannelGroupFromUser.h
            PVRChannelGroupMember.h
            PVRChannelGroupSettings.h
            PVRChannelGroups.h
            PVRChannelGroupsContainer.h
            PVRChannelNumber.h
            PVRRadioRDSInfoTag.h
            PVRChannelsPath.h)

core_add_library(pvr_channels)
