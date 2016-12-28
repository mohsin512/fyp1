
from __future__ import unicode_literals
from django.http import HttpResponse 
from django.shortcuts import render

from django.shortcuts import render

# Create your views here.

def input(request):
  
  your_parameter=request.GET['parameter']
  request.session['num']=your_parameter 
  return HttpResponse(your_parameter)

def output(request):
      return HttpResponse(request.session.get('num'))





