Usage
=====

import 'package:mimetypes/mimetypes.dart';

main(){

  var mimetype = guessType('foo.html');
  if(mimetype == null)
    mimetype = 'application/octet-stream';

}