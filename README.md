# CS110 Final Project

# Alien Invasion

class
class Setting():
    def_int_(self):
        self.screen_width=1600
        self.screen_height=900
        self.bg_color=(230,230,230)
class Ship():
    def_init_(self,screen):
        self.screen=screen
        self.image=pygame.imageload('images/ship.bmp')
        self.rect=self.image.get_rect()
        self.screen_rect=screen.get_rect()
        self.rect.conterx=self.screen_rect.centerx
        self.rect.bottom=self.screen_rect.bottom
    def blime(self)
        self.screen.blit(self.image,self.rect)

class Bullet(Sprite):
    def_int_(self,ai_setting,screen,ship):
        super(Bullet,self)._int_()
        self.screen=screen
        self.rect=pygame.Rect(0,0,ai_settings.bullet_width,ai_setting.bullet_height)
        self.rect.centerx=ship.rect.centex
        self.rect.top=ship.rect.top
        self.y=float(self.rect.y)
        self.color=ai_setting.bullet_color
        self.speed_factor=ai_settings.bullet_speed_factor

class Alien(Sprite):
    def_int_(self,ai_setting,screen)
       super(Alien,self)._int_()
       self.screen=screen
       self.ai_settting=ai_settings
       self.image=pygame.image.load('images/alien.bmp')
       self.rect=self.rect.height
       self.x=float(self.rect.x)
   def blitme(self):
       self.screen.blit(self.image,self.rect)
