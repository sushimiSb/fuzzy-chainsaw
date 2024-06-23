from setuptools import setup

def readme():
    return '''
readme2tex
==========

Renders LaTeX for Github Readmes.
  
See https://github.com/leegao/readme2tex/
'''

setup(name='readme2tex',
      version='0.0.1b3',
      description='Render LaTeX within your Github Readmes',
      long_description=readme(),
      url='http://github.com/leegao/readme2tex',
      author='Lee Gao',
      author_email='lg342@cornell.edu',
      license='MIT',
      packages=['readme2tex'],
      classifiers=[
          'Development Status :: 3 - Alpha',
          'License :: OSI Approved :: MIT License',
          'Programming Language :: Python :: 2.7',
          'Topic :: Text Processing :: Markup :: LaTeX',
      ],
      keywords='github readme markdown latex tex equations math svg markup',
      install_requires=[
          'markdown',
          'pygments',
          'cairosvg==1.0.22',
      ],
      include_package_data=True,
      zip_safe=False)
