STATIC_URL = '/static/'

MEDIA_URL = '/media/'

  

if DEBUG:

  STATICFILES_DIRS = [os.path.join(BASE_DIR, 'static')]

else:

  STATIC_ROOT = os.path.join(BASE_DIR, 'static')

  

MEDIA_ROOT = os.path.join(BASE_DIR, 'media')
