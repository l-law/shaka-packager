HLS specific stream descriptor fields
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

:hls_name:

    Used for HLS audio to set the NAME attribute for EXT-X-MEDIA.
    Defaults to the base of the playlist name.

:hls_group_id:

    Used for HLS audio to set the GROUP-ID attribute for EXT-X-MEDIA.
    Defaults to 'audio' if not specified.

:playlist_name:

    Used for HLS to name the playlist for the stream. Usually ends
    with '.m3u8'. If unspecified, defaults to something of the form
    'stream_0.m3u8', 'stream_1.m3u8', 'stream_2.m3u8', etc.
