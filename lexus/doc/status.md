# Status (keep in mind i haven't tested most stuff yet!)
## General
- [x] System boots
- [x] Camera app starts
- [x] Camera app can get privileged video stream
- [ ] Filters take effect (not tested)
- [x] Flash works
- [ ] Gallery works (clicking doesnt do anything, the smali patch for gallery app needs to be revised)
- [x] SeLinux enforcing
## Photo
- [x] Preview renders
- [x] Preview lens switch transition renders
- [x] Manual lens switch and zoom works for back cameras
- [x] Manual zoom works for front camera
- [x] OIS when using main camera
- [ ] Action mode (60fps preview) works (i dont think nord 5 has this)
- [x] Can take photo without crash
## Video
- [x] Preview renders
- [x] Lens switch and zoom works
- [ ] All formats with SDR color space (not tested)
- [ ] HDR Dolby Vision (do we have this?)
- [x] EIS for ultra wide camera
- [x] HIS (OIS+EIS) for main camera
- [x] Ultra Steady
- [x] Can record video and save to file
## Master (not tested)
- [x] Preview renders
- [ ] Lens switch and zoom works
- [ ] Adjusting params takes effect
- [ ] Can take photo in JPG format and save to file
- [ ] Can take photo in RAW format and save to file
## Portrait (for now works only in front cam, crashes app when switching to 1x on rear cam. i suspect a leftover from giuliac)
- [x] Preview renders
- [ ] Lens switch works
- [x] Effects like blur works
- [x] Can take photo and save to file
## Slow Motion
- [ ] Preview renders
- [x] All formats (720p/1080p 240fps/480fps) works
- [x] Can record video and save to file
- [x] Manual lens switch works
## Dual Video (tf is this? not tested)
- [ ] Preview renders
- [ ] All layouts work
- [ ] Back camera zoom works
- [ ] Can record video and save to file
## Movie (not tested)
- [ ] Preview renders
- [ ] Ultra^2 Steady works
- [ ] Lens switch works
- [ ] EIS for ultra wide camera
- [ ] HIS (OIS+EIS) for main camera
- [ ] Adjusting params takes effect
- [ ] Can record video and save to file
## Other Modes
- [ ] Untested or broken
