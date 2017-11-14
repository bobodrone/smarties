# GULP

## Typical errors on LINUX

### Unhandles 'error' event (events.js:183)

**Solution**:    
`echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p`

