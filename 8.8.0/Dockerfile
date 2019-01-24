FROM haxe:3.4.7

RUN haxelib install lime 7.2.1
RUN haxelib install openfl 8.8.0
RUN yes | haxelib run openfl setup

RUN cp "/haxelib/lime/7,2,1/templates/bin/lime.sh" /usr/local/bin/lime
RUN chmod 755 /usr/local/bin/lime
RUN cp "/haxelib/openfl/8,8,0/assets/templates/bin/openfl.sh" /usr/local/bin/openfl
RUN chmod 755 /usr/local/bin/openfl

CMD [ "openfl" ]